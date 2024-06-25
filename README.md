![image](https://github.com/TechwTre/jira-configuration/assets/126909509/fbd83725-b407-4253-b843-b910fdb962f4)

<h1> Jira Service Management: Configuration, Workflows and Automation </h1>

This project aims to enhance IT support efficiency by leveraging Jira's robust capabilities. The focus is on meticulously configuring Jira settings, creating efficient workflows, and implementing intelligent automation rules. By customizing issue types, fields, screens, and automation rules, a streamlined and effective pathway is established for each ticket, ensuring a smooth transition from reporting to resolution.
</p>

<h2>Objectives</h2>

<h4> Streamline Ticket Management: </h4>

- Simplify the process of creating, tracking, and managing tickets through customized workflows and fields tailored to various types of IT support requests.

<h4> Automate Routine Tasks: </h4>

- Implement automation rules to handle repetitive tasks such as ticket assignments, status updates, and notifications.

<h4> Enhance Communication: </h4>

- Facilitate better communication within the support team and with end-users through automated notifications and updates.

</p>

<h2> Environments and Technologies Used </h2>

- Jira Service Management 
- Windows 11

<h2> Customizing Issue Types </h2>

Jira allows you to customize the types of issues that can be created within your project. This is essential for categorizing the different kinds of requests and problems your help desk will handle.
</p>

![image](https://github.com/TechwTre/jira-configuration/assets/126909509/7aec01a5-d8a2-433a-8aa2-dfe50c9695b3)
</p>
<br>

<h3> Standard Issue Types for IT Help Desk: </h3>

1. Bug Report 
</p>

![image](https://github.com/TechwTre/jira-configuration/assets/126909509/2d77b8a9-ddfb-45d7-8406-efc5a00a3329)
</p>
<br>

2. Hardware Request 
</p>

![image](https://github.com/TechwTre/jira-configuration/assets/126909509/24ce1ba1-122a-4f74-be79-1ae6d815abe0)
</p>
<br>

3. Software Installation
</p>

![image](https://github.com/TechwTre/jira-configuration/assets/126909509/2551a4cd-78fb-45fe-96ef-bc18bbcf4b78)
</p>
<br>

4. Network Issue  
</p>

![image](https://github.com/TechwTre/jira-configuration/assets/126909509/3c326839-699a-4811-ac33-6d14341db943)
</p>
<br>

5. Access Request
</p>

![image](https://github.com/TechwTre/jira-configuration/assets/126909509/fafd3911-be4c-470c-951e-bb9330a8d71b)
</p>
<br>

<h2> Defining a Workflow </h2>

A workflow defines the lifecycle of an issue, from creation to resolution. Customizing the workflow allows you to mirror your organization's process for handling IT support requests.
</p>

![image](https://github.com/TechwTre/jira-configuration/assets/126909509/ac8cfd4e-b804-4850-bd0c-4e8aa72bd225)
</p>
<br>

<h3>Standard Workflow Stages for IT Help Desk: </h3>

![image](https://github.com/TechwTre/jira-configuration/assets/126909509/62d4fc6d-de34-46f7-a018-5649b7bdd244)
</p>
<br>

- Open:</strong> The initial status of a new issue.
</p>

- In Progress:</strong>The issue is being worked on by IT staff.
</p>

- Awaiting User:</strong> Waiting for more information or confirmation from the user.
</p>

- Resolved:</strong> The issue has been addressed, awaiting closure.
</p>

- Closed:</strong> The issue is fully resolved and closed.
</p>

![image](https://github.com/TechwTre/jira-configuration/assets/126909509/b351e617-0085-4340-96c5-925a157013d1)
</p>
<br>

<h2>Custom Fields</h2>

Custom fields allow you to capture specific information related to different issue types. 
</p>

![image](https://github.com/TechwTre/jira-configuration/assets/126909509/fd9e694a-a058-44e2-8148-113640e5e2b5)

- Severity Level:</strong> Helps prioritize issues based on their impact on the business.
</p>

- Affected System:</strong> Identifies which system or application is impacted by the issue. 
</p>

- Reported By:</strong> Captures whether the issue was reported by an employee, customer, or vendor. 
</p>
  
- Expected Resolution Time:</strong> Provides an estimate of how long it will take to resolve the issue, which can be crucial for managing expectations.
</p>

- Root Cause Analysis:</strong> A text field for documenting the underlying cause of the issue once it has been identified. This is valuable for preventing future occurrences.
</p>
<br>

<h2>Customizing Screens</h2>

Screens in Jira determine which fields are displayed to users when they create, view, or edit an issue. Customizing these screens allows you to ensure that users are prompted for all relevant information when reporting an issue or moving it through its lifecycle.
</p>

![image](https://github.com/TechwTre/jira-configuration/assets/126909509/5a5255a2-97d2-4bbd-8bb5-4986ade64e62)
</p>
<br>

<h2>Understanding Jira Automation</h2>

Jira Automation is a powerful tool that allows you to create rules based on triggers, conditions, and actions. These rules can automate various aspects of your workflow, from issue assignment to notifications and field updates.
</p>

![image](https://github.com/TechwTre/jira-configuration/assets/126909509/02fe1f17-e010-42f6-b633-e4e5204f3768)
</p>
<br>

<h3>Key Concepts for Automation</h3>

- Triggers:</strong> What initiates the automation rule. For example, creating an issue, updating an issue, or transitioning an issue could be triggers.
</p>

- Conditions:</strong>  Criteria that must be met for the automation rule to execute. 
Conditions help ensure that actions are taken only when relevant.
</p>

- Actions:</strong>  The operations performed when the trigger fires and the conditions are met. Actions can include updating an issue, sending an email, or transitioning an issue to a different status.
</p>

<h3>Examples of Automation Rules for an IT Help Desk</h3>

Auto-Assigning Issues Based on Severity or Type
</p>

- Trigger: Issue created.
- Condition: Check the issue's severity or type (e.g., "Critical" severity or "Network Issue" type).
- Action: Assign the issue to a specific user or group responsible for that type of issue.

<img width="403" alt="Example 1" src="https://github.com/kirkgacias/jira-configuration/assets/158519921/3a1792b1-9bba-432b-9b3f-a8afa2f37bec">

Notifying Team Members of High-Severity Issues
</p>

- Trigger: Issue created with a "Critical" severity.
- Condition: Issue severity is set to "Critical."
- Action: Send an email notification to the Admins

<img width="624" alt="Example 2" src="https://github.com/kirkgacias/jira-configuration/assets/158519921/545e840c-c7ee-4cbc-9fc1-2597003b9213">

Automated Reminders for Pending Issues
</p>

- Trigger: Scheduled trigger (e.g., run daily).
- Condition: Check for issues in "In Progress" status for more than a specified time (e.g., 3 days).
- Action: Send a reminder to the assignee or post a comment on the issue.

<img width="624" alt="pending issues" src="https://github.com/kirkgacias/jira-configuration/assets/158519921/58321453-d43a-460a-b9e1-861fa8fdf4ac">


<h2> Conclusion</h2>

The "Jira Service Management: Configuration, Workflows, and Automation" project showcases the various features of Jira that optimize IT service management processes. By carefully configuring Jira Service Management, designing efficient workflows, and implementing smart automation, organizations can significantly improve the speed, accuracy, and quality of their IT services.
</p>



