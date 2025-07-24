# 🧪 Test Case: "Shared Services Agent" to assign ticket to other Resolver Group

**Scenario ID:** 14  
**Role:** Shared Services Agent


## 🔢 Steps:

**Step 1:** Go to the AskHR ticket section and open/review the existing ticket  
➡️ **Expected Result:** Shared service agent is able to view the ticket in AskHR successfully

**Step 2:** Assign ticket to self or to team member  
➡️ **Expected Result:** Shared service agent is able to assign the ticket himself / herself successfully

**Step 3:** Go to the "overview" section and review the ticket content  
➡️ **Expected Result:** Shared service agent is able to review the content

**Step 4:** Click "Service and Support Team" section and select the appropriate Resolver Group name  
➡️ **Expected Result:** Shared service agent is able to update the other resolver group name successfully

**Step 5:** Remove the Advisor name from the "Assigned To" section  
➡️ **Expected Result:** Shared service agent is able to remove advisor name successfully

**Step 6:** Go to the "Notes" section and put relevant notes for the other resolver group and click on "Save"  
➡️ **Expected Result:** Shared service agent is able to update notes/comments in notes section successfully


---

# 🧪 Test Case: "Shared Services Agent" to convert tickets created through unassociated emails

**Scenario ID:** 13  
**Role:** Shared Services Agent


## 🔢 Steps:

**Step 1:** Click on the "Unassociated emails" section and check that email received from ex-employee/3rd party/agencies  
➡️ **Expected Result:** Shared service agent is able to open the unassociated emails successfully

**Step 2:** Click and review the new email content  
➡️ **Expected Result:** Shared service agent is able to review the content

**Step 3:** Click "Actions" option on the right top of the AskHR to convert the email into a new ticket (Please update the employee field, correct topic, sub-topic and the resolver group name  
➡️ **Expected Result:** Shared service agent is able to update all the mandate field successfully

**Step 4:** Click on "Save and open" at the right bottom of the AskHR page  
➡️ **Expected Result:** Shared service agent is able to convert the email into a ticket successfully

**Step 5:** Goto the AskHR ticket section and validate that the ticket is visible  
➡️ **Expected Result:** Shared service agent is able to view the ticket in AskHR successfully

**Step 6:** Click the ticket and go to the "overview" section and Identify Sender / Authenticate Sender / Verify request  
➡️ **Expected Result:** Shared service agent is able to authenticate the sender successfully

**Step 7:** Assign ticket to self  
➡️ **Expected Result:** Shared service agent is able to assign the ticket himself / herself successfully

**Step 8:** Go to "interactions", click on "New" in the pop up window, choose "Email", write your e-mail and click send  
➡️ **Expected Result:** Shared service agent is able to reply back the sender successfully

**Step 9:** Set ticket "Status" to "Solution Provided", click "Save" wait for response from Employee/ Requestor  
➡️ **Expected Result:** Shared service agent is able to update the status successfully


---

# 🧪 Test Case: Automatic ticket plus workflow closure

**Scenario ID:** 18  
**Role:** Technical (Run Team)


## 🔢 Steps:

**Step 1:** Login to SF SD and navigate to the Services > tickets  
➡️ **Expected Result:** Ticket overview Page is visible

**Step 2:** Open the workflow ticket  
➡️ **Expected Result:** Action was taken successfully

**Step 3:** View the link maintainted on Workflow section of the ticket .  
➡️ **Expected Result:** Link successfully redirects to related Workflow

**Step 4:** Verify the Workflow in EC  
➡️ **Expected Result:** Agent can either approve/update/send back the workflow

**Step 5:** Close ticket  
➡️ **Expected Result:** Ticket is successfully closed


---

# 🧪 Test Case: Employee to access and navigate in SF SD module

**Scenario ID:** 1  
**Role:** Employee


## 🔢 Steps:

**Step 1:** Go to URL:  <insert link to SF UAT environment>  
➡️ **Expected Result:** User is able to login successfully

**Step 2:** Check the Home drop down, To-do list, Ask-HR and Notifications icons at the top  
➡️ **Expected Result:** Home drop down, To-do list, Ask-HR and Notifications are available

**Step 3:** Go to the "People Service Center" icon at the top right part of the home page of SuccessFactors:  
➡️ **Expected Result:** Pop up window for People Service Center loads correctly displaying "Search Knowledge base", "Create Ticket" and "Tickets Overview" windows

**Step 4:** Click on  "Search Knowledge base"  
➡️ **Expected Result:** "Search Knowledge base" is displayed correctly

**Step 5:** Click on the back arrow next to People Service Center  
➡️ **Expected Result:** Window for People Service Center loads correctly displaying "Search Knowledge base", "Create Ticket" and "Tickets Overview" windows

**Step 6:** Click on  "Create Ticket"  
➡️ **Expected Result:** "Create Ticket"  is displayed correctly

**Step 7:** Click on the "Cancel" button at the bottom right of the page  
➡️ **Expected Result:** Window for People Service Center loads correctly displaying "Search Knowledge base", "Create Ticket" and "Tickets Overview" windows

**Step 8:** Click on  "Tickets Overview"  
➡️ **Expected Result:** "Tickets Overview" is displayed correctly

**Step 9:** Go to the "Ask HR" icon at the top right part of the home page of SuccessFactors:  
➡️ **Expected Result:** Pop up window for People Service Center loads correctly displaying "Search Knowledge base", "Create Ticket" and "Tickets Overview" windows

**Step 10:** Click on "Create Ticket - Report an Issue" tile  
➡️ **Expected Result:** "Create New Ticket" window loads properly

**Step 11:** Select a Service Category and an Incident Category, "View suggesstions" will appear, click on it  
➡️ **Expected Result:** Suggestions of knowledge base articles are displayed on the right side of the screen properly


---

# 🧪 Test Case: Employee to create an enquiry via People Service Center

**Scenario ID:** 2  
**Role:** Employee


## 🔢 Steps:

**Step 1:** Click on "Create Ticket - Report an Issue" tile  
➡️ **Expected Result:** "Create New Ticket" window loads properly

**Step 2:** In "Topic", select service category in the drop down  (Eg : Employment Data Changes) - You can refer to column E categories in country specific ECSC Workbook  
➡️ **Expected Result:** User is able to choose the Topic

**Step 3:** In "Sub Topic", select incident category in the drop down (Eg. Employment Data Changes - Queries)  
➡️ **Expected Result:** User is able to choose the Sub topic.

**Step 4:** In "Subject",  indicate the subject of your request (Eg. Employee data change)  
➡️ **Expected Result:** User is able to add subject

**Step 5:** In "Attachments", click on "upload" to add attachments (attachments are limited to 20MB & are not mandatory)  
➡️ **Expected Result:** User is able to upload attachment

**Step 6:** In "Description", add the description of your request  
➡️ **Expected Result:** User is able to add description

**Step 7:** Click on "Submit"  
➡️ **Expected Result:** Ticket is created successfully

**Step 8:** Click on "Tickets Overview - Track your service requests"  
➡️ **Expected Result:** "Tickets Overview" "MyTickets" loads properly, submitted tickets are visible

**Step 9:** Check if message "All "Closed" tickets are hidden. View them by enabling the filter or by using the search option." is displayed below the search field  
➡️ **Expected Result:** Message All "Closed" tickets are hidden. View them by enabling the filter or by using the search option.is displayed

**Step 10:** Click on a ticket, check if ticket status (e.g. New), Service Category, Ticket no. and Ticket information details are correct  
➡️ **Expected Result:** Ticket status (e.g. New), Service Category, Ticket no. and Ticket information details are displayed correctly

**Step 11:** Click on a ticket you have created, click on "edit ticket" at the bottom of the ticket  
➡️ **Expected Result:** User is able to edit ticket

**Step 12:** Click on the "Conversation" tab to add comments, click on "Attachments" tab to upload documents then "Submit"  
➡️ **Expected Result:** User is able to submit new comments, attachments in an open ticket

**Step 13:** Click on a ticket you have created, click on "Close ticket" at the bottom of the ticket  
➡️ **Expected Result:** Ticket is closed properly

**Step 14:** Click on "Tickets Overview - Track your service requests", click on the setting icon at the bottom of the page  
➡️ **Expected Result:** Setting icon loads properly

**Step 15:** Close a ticket, refresh the page, click on interaction, click on "New"  
➡️ **Expected Result:** Adding changes is  not possible (please note that adding attachments is possible)

**Step 16:** Click on AskHR and check if ticket is created  
➡️ **Expected Result:** Ticket is not created

**Step 17:** Shared Service agent log in and check new tickets  
➡️ **Expected Result:** E-mail is received under blocked emails, a ticket will not be created


---

# 🧪 Test Case: Exited employee is not able to access SF

**Scenario ID:** 3  
**Role:** Exited employee


## 🔢 Steps:

**Step 1:** Go to URL: <insert link to SF UAT environment> try to login  
➡️ **Expected Result:** Exited employee is not able to log in into SF


---

# 🧪 Test Case: Exited employee to send an enquiry via e-mail

**Scenario ID:** 4  
**Role:** Exited employee


## 🔢 Steps:

**Step 1:** Send an enquiry via e-mail from the external e-mail address:  <insert e-mail> to the internal e-mail address:  <insert e-mail>  
➡️ **Expected Result:** E-mail is received and a ticket will be created with the source as "e-mail"

**Step 2:** Click on AskHR and check if ticket is created under unassociated emails (refer to line 109)  
➡️ **Expected Result:** Ticket is created in AskHR


---

# 🧪 Test Case: Replicate employee data (from EC to AskHR)

**Scenario ID:** 17  
**Role:** Technical (Run Team)


## 🔢 Steps:

**Step 1:** Proceed to Add a new employee into SuccessFactors following the New Hire wizard in SuccessFacotors  
➡️ **Expected Result:** Check that employee is hired and has a First name, Last name, email and numeric employee ID in Employee Profile iNote: The action is taken in Sucessfacotors (EC)

**Step 2:** Log into Cloud for Customer (AskHR) as an admin user (refer to Shared Services Agent V.1)  
➡️ **Expected Result:** Note: Employee sync job will run twice on daily basis, which will replicate the employee from SF EC to C4C.

**Step 3:** Within AskHR, go to the Administrator work access tab, click General Settings  
➡️ **Expected Result:** All workcenters are visible correctly.

**Step 4:** Within the adminstator workCenter, click Web Service Message Monitoring (found under System Administration)  
➡️ **Expected Result:** check if jobs are successful.

**Step 5:** Under business user tab, search for employee that was hired into SuccessFactors.  
➡️ **Expected Result:** If they are displayed, and verify the details of the employee.


---

# 🧪 Test Case: Shared Services Agent to access and navigate in SF SD

**Scenario ID:** 5  
**Role:** Shared Services Agent


## 🔢 Steps:

**Step 1:** Click on URL:  <insert link to SF UAT environment>  
➡️ **Expected Result:** User is able to login to SuccessFactors Service Delivery module successfully

**Step 2:** Check the Home drop down, To-do list, Ask-HR and Notifications icons at the top  
➡️ **Expected Result:** Home drop down, To-do list, Ask-HR and Notifications are available

**Step 3:** Click on the "Ask HR-Shared Service Login" tile at the "Organizational Updates" section at the bottom of the page  
➡️ **Expected Result:** Shared Services Agent is able to login to AskHR successfully


---

# 🧪 Test Case: Shared Services Agent to access and view tickets and verify details

**Scenario ID:** 6  
**Role:** Shared Services Agent


## 🔢 Steps:

**Step 1:** Click on the "Ask HR-Shared Service Login "Tile", click on "my tickets" tile  
➡️ **Expected Result:** Shared Services Agent is able able to access "my open tickets" successfully

**Step 2:** Click on ticket ID to open and view the ticket, verify details  
➡️ **Expected Result:** Shared Services Agent is able to view ticket details and verify details


---

# 🧪 Test Case: Shared Services Agent to create a ticket on behalf of the employee

**Scenario ID:** 9  
**Role:** Shared Services Agent


## 🔢 Steps:

**Step 1:** Navigate to the tickets tab under "Service Work Center", click on "+" icon to create a ticket  
➡️ **Expected Result:** "Create New Ticket" window loads properly

**Step 2:** Provide the necessary information about the employee, type of ticket, subject, source, and detailed description of the request,  click save and open  
➡️ **Expected Result:** Agent is able to fill the necessary information of the ticket

**Step 3:** Click on "+" icon to create a ticket, provide the necessary information about the employee, type of ticket, subject, source, and detailed description of the request, click "Submit"  
➡️ **Expected Result:** "Create New Ticket" window loads properly, Shared Services Agent is able to provide necessary information, ticket is submitted successfully


---

# 🧪 Test Case: Shared Services Agent to create an enquiry from AskHR

**Scenario ID:** 7  
**Role:** Shared Services Agent


## 🔢 Steps:

**Step 1:** Click on "+" icon to create a ticket  
➡️ **Expected Result:** Shared Services Agent is able to view ticket details and verify details

**Step 2:** Provide the necessary information about type of ticket, subject, source, and detailed description of the request,  click save and open  
➡️ **Expected Result:** User is able to open ticket successfully


---

# 🧪 Test Case: Shared Services Agent to create sub tickets

**Scenario ID:** 11  
**Role:** Shared Services Agent


## 🔢 Steps:

**Step 1:** Login to SF SD and navigate to the Services > tickets  
➡️ **Expected Result:** Workcerter opens sucessfully and tickets are visible

**Step 2:** Cick on"+" icon to create a ticket  
➡️ **Expected Result:** Ticket is submitted

**Step 3:** Once the ticket is created, open  a parant ticket and navigate to Subticket tab  
➡️ **Expected Result:** Subticket tab is visible

**Step 4:** Click on "Add subticket",  fill in the previously created ticket number, click save  
➡️ **Expected Result:** Subticket is added successfully

**Step 5:** Close the subticket, ensure that survey is triggered  
➡️ **Expected Result:** Survey is  trriggered when sub ticket is closed

**Step 6:** In tickets overview, check field " Sub ticket closure indicator" is set as "yes"  
➡️ **Expected Result:** Sub ticket closure field is set as "yes"


---

# 🧪 Test Case: Shared Services Agent to use "Search" bar and "Advanced Search" bar to search for a specific ticket

**Scenario ID:** 8  
**Role:** Shared Services Agent


## 🔢 Steps:

**Step 1:** Click on the search bar In the ticket overview tab, click on the "funnel" icon to execute an advanced search, access a keyword for your search, access keywords, click on "Go"  
➡️ **Expected Result:** Shared Services Agent is able to use the search bar, advanced search funnel and results are displayed properly

**Step 2:** Click on the pencil icon to edit, click on "Priority" to display the list of priorities and choose priority: "Urgent", "Normal", "Low", "Immediate"  
➡️ **Expected Result:** Shared Services Agent is able to define new ticket priority

**Step 3:** Click on "+" icon to create a ticket, specify "employee" you are raising the ticket for  
➡️ **Expected Result:** Create ticket tab loads properly

**Step 4:** ,  
➡️ **Expected Result:** Shared Services Agent is able to select country in "Type"

**Step 5:** In "Topic", verify if all the topics and sub topics are availables (you can refer to column H categories in ECSC Workbook) then choose a topic (Eg. New Joiner)  
➡️ **Expected Result:** Shared Services Agent is able able to verify topics and sub topics

**Step 6:** Verify if all the 16 global Resolver Groups are available. Please see them in column K  
➡️ **Expected Result:** Shared Services Agent is able able to verify all 16 global Resolver Groups

**Step 7:** In "Team", verify that your agent team is available  
➡️ **Expected Result:** Shared Services Agent is able to select his team in "Team"

**Step 8:** In "Subject",  indicate the subject of your request (Eg. New Hire)  
➡️ **Expected Result:** Shared Services Agent is able to indicate the subject of his request in "Subject"

**Step 9:** In "Source", select type of ticket : Automatic, Chat, Manual Data Entry, Telephony, Workzone  
➡️ **Expected Result:** Shared Services Agent is able to select the source of the ticket

**Step 10:** In "Sub topic", select a sub topic (Eg. New start date)  
➡️ **Expected Result:** Shared Services Agent is able to select the sub topic

**Step 11:** In "Description", add the description of your request  
➡️ **Expected Result:** Shared Services Agent is able to add description of the ticket

**Step 12:** Click on "Save and open"  
➡️ **Expected Result:** Shared Services Agent is able to properly open the ticket

**Step 13:** Click on "Overview" to access and edit aditionnal information, employee information, click on "save"  
➡️ **Expected Result:** Shared Services Agent is able to access ticket overview and edit information

**Step 14:** Click on "Interactions", click on "New" to add comments in the memo tabs, click on "save"  
➡️ **Expected Result:** Shared Services Agent is able to add comments

**Step 15:** Click on "Search Knowledge Base" to access knowledge base and view suggested articles  
➡️ **Expected Result:** Shared Services Agent is able to view knowledge base articles

**Step 16:** Click on "Attachments" to add and remove attachments in the ticket, click "save"  
➡️ **Expected Result:** Shared Services Agent is able to add and remove attachments

**Step 17:** Click on "Changes" to dispaly change history  
➡️ **Expected Result:** Shared Services Agent is able to diplay and add changes

**Step 18:** Click on "Solution Center" to view similar tickets and given solutions  
➡️ **Expected Result:** Shared Services Agent is able to access "Solution Center" and view similar tickets

**Step 19:** In the ticket overview tab, click on the action tab, choose ticket ID to open and view the ticket, click on the "Action" tab, choose "Add note", add your note and click "OK"  
➡️ **Expected Result:** Action tab is visible and note is added

**Step 20:** Ask the Requestor/Employee/employee to verify if the note is visible to them  
➡️ **Expected Result:** Note is only visible to Shared Services Agent, and is not visible to the Requestor/Employee/employee

**Step 21:** Go to "interactions", click on "New" in the pop up window, choose "Email", write your e-mail and click send  
➡️ **Expected Result:** Email window loads properly and e-mail is sent successfully

**Step 22:** Click on "interactions" , scroll up and down using the arrow keys to see new response and previous interaction  
➡️ **Expected Result:** Shared Services Agent is able to scroll and see the interactions

**Step 23:** Click on the pencil icon to edit, in the "Status" tab, click to display the list and choose statuses: In Process-By Agent, In Process-Waiting for Employee, In Process-Awaiting Third Party, Closed, Solution Provided  
➡️ **Expected Result:** Shared Services Agent is able to verify ticket "Status"

**Step 24:** Set ticket "Status" to "Solution Provided", click "Save" wait for response from Employee/ Requestor  
➡️ **Expected Result:** Ticket is resolved properly by Shared Services Agent and waits for an answer from Requestor/Employee

**Step 25:** Log in as an Emloyee and confirm resolution  
➡️ **Expected Result:** Ticket is closed automatically and survey is triggered

**Step 26:** In the ticket overview tab, click on my tickets, check the status of the ticket  
➡️ **Expected Result:** Ticket is closed successfully

**Step 27:** Close a ticket, refresh the page, click on attachments, click add, click on interaction, click on "New"  
➡️ **Expected Result:** Adding changes is not possible, attachment added successfully

**Step 28:** Verify if e-mail survey is triggered to Requestor/Employee  
➡️ **Expected Result:** E-mail survey is sent successfully

**Step 29:** Open the e-mail,  give feedback via survey  
➡️ **Expected Result:** E-mail is received by Requestor/Employee and survey is successfully answered

**Step 30:** Log in as an Emloyee and reject resolution. Note : Comments need to be added before rejecting solution  
➡️ **Expected Result:** Ticket returns to status "in process-by agent"


---

# 🧪 Test Case: Shared Services Agent to verify Auto assignment based on ECSC workbook

**Scenario ID:** 12  
**Role:** Shared Services Agent


## 🔢 Steps:

**Step 1:** Cick on"+" icon to create a ticket, complete the topic and sub topic, subject and description  
➡️ **Expected Result:** Ticket is created successfully

**Step 2:** Once the ticket is created, click to open it and verify the assigned group  
➡️ **Expected Result:** The ticket is assigned auomatically to the resolver group as per Workbook depending on the chosen topic and sub topic

**Step 3:** Cick on"+" icon to create a ticket, click to open the ticket, click on "Action", choose "Assign to myself"  
➡️ **Expected Result:** The ticket is manually assigned to the agent


---

# 🧪 Test Case: Shared Services Agent to verify survey

**Scenario ID:** 10  
**Role:** Shared Services Agent


## 🔢 Steps:

**Step 1:** Close the ticket and verify if e-mail survey is triggered to Requestor/Employee  
➡️ **Expected Result:** Ticket is closed and e-mail survey is triggered successfully

**Step 2:** Open the e-mail,  open the inclosed survey, give your feedback and submit  
➡️ **Expected Result:** Requestor is able to give feedback

**Step 3:** Create a ticket on behalf of the employee (see steps in test case "create ticket on behalf of the employee)  
➡️ **Expected Result:** Ticket is created successfully

**Step 4:** Resolve and change status to "Solution Provided"  
➡️ **Expected Result:** Ticket is resolved and closed successfully

**Step 5:** Verify if e-mail survey is triggered to Requestor/Employee and survey is only sent to the requestor  
➡️ **Expected Result:** Survey is triggered to the requestor


---

# 🧪 Test Case: Shared Services Agents/HRBP/COC to Resolve tickets

**Scenario ID:** 16  
**Role:** Shared Services Agent/HRBP/COC to resolve tickets


## 🔢 Steps:

**Step 1:** Login to Successfactors and Go to employee Profile  
➡️ **Expected Result:** Login is successful and employee profile is visible

**Step 2:** Take new action on the user to trigger a workflow  
➡️ **Expected Result:** workflow was sucessfully triggered

**Step 3:** Login to SF SD and navigate to the Services > tickets  
➡️ **Expected Result:** Tickets overviw is opened properly

**Step 4:** Click on ticket ID to open the ticket  - Please note that automatic workflow tickets take between 8 to 30 min to be created in SD  
➡️ **Expected Result:** After a period between 8 to 30 min workflow ticket is created

**Step 5:** Resolve ticket  
➡️ **Expected Result:** After a period between 8 to 30 min workflow ticket is created


---

# 🧪 Test Case: Shared services Agent to verify SLA calculation when ticket is in "new" for all topics and subtopics of the respective country

**Scenario ID:** 15  
**Role:** Shared Services Agent


## 🔢 Steps:

**Step 1:** Cick on"+" icon to create a ticket, click to open the ticket, in ticket overview chronology, verify if SLA is assigned as per the ECSC workbook for all topics and subtopics of the respective country  
➡️ **Expected Result:** SLA for assignment is as per the workbook

**Step 2:** Change the Ticket status to Awaiting employee/ awaiting- third party/solution confirmed and solution provided, verify whether SLA is paused for all topics and subtopics of the respective country  
➡️ **Expected Result:** SLA for assignment is paused

**Step 3:** Close the ticket, verify if SLA is completed for all topics and subtopics of the respective country  
➡️ **Expected Result:** SLA is successfully completed


---
