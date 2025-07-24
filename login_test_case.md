# 🧪 Caso de Teste: Registo de Utilizador com Verificação por E-mail

## 🆔 ID: TC-REG-001  
## 🎯 Objetivo do Teste:
Verificar se o utilizador consegue efetuar o registo na aplicação com dados válidos e concluir a verificação através de um link enviado por e-mail.

---

## 📝 Pré-condições:
- A aplicação web está acessível no ambiente de testes.
- O utilizador tem acesso a uma conta de e-mail funcional (ex: mailtrap.io, mailinator.com ou email real de teste).
- A base de dados está limpa (sem utilizadores pré-existentes com o mesmo email).

---

## 🔢 Passos do Teste:

| Passo | Ação | Dados de entrada | Resultado Esperado |
|------|------|------------------|---------------------|
| 1 | Aceder à página de registo | N/A | Página de registo carregada com sucesso |
| 2 | Preencher o formulário de registo | Nome: João Silva<br>Email: joao.silva@test.com<br>Password: Teste123! | Os campos são preenchidos corretamente |
| 3 | Submeter o formulário | Clicar em "Registar" | Mensagem de confirmação de registo enviada para o e-mail |
| 4 | Aceder ao e-mail do utilizador | Email: joao.silva@test.com | Receção de e-mail de verificação com link |
| 5 | Clicar no link de verificação no e-mail | URL do e-mail | Página de confirmação de conta com mensagem de sucesso |
| 6 | Aceder à aplicação e efetuar login | Email: joao.silva@test.com<br>Password: Teste123! | Acesso concedido ao dashboard do utilizador |

---

## ✔️ Resultado Esperado Final:
- A conta do utilizador é criada e verificada com sucesso.
- O utilizador consegue iniciar sessão na aplicação após a ativação.

---

## 🚫 Critérios de Falha:
- Não receção do e-mail de verificação em 2 minutos.
- Link de verificação expirado ou com erro.
- Login não autorizado após ativação.

---

## 🛠️ Notas Técnicas:
- Endpoint de registo: `POST /api/users/register`
- Endpoint de ativação: `GET /verify/{token}`
- DB check opcional: verificar se o campo `email_verified = true` na tabela `users`

---

## 🔍 Referências:
- Plano de Testes Funcionais – Módulo de Autenticação
- Documento de Requisitos v2.1
