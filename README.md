<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

In this lab, I guide you through the complete lifecycle of a support ticket, from initial intake to final resolution, using the open-source help desk ticketing system, osTicket. This comprehensive walkthrough demonstrates how to effectively utilize osTicket's features to manage and resolve support requests in a real-world environment.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>
**Creating and Submitting Tickets in osTicket**

To create and submit tickets in osTicket, follow these steps:

1. **Access the Ticket Portal**
   - Open your web browser and navigate to the osTicket portal URL.
   - If prompted, enter your login credentials to access the portal.

2. **Submit a New Ticket**
   - Click on the **Submit a Ticket** button or link within the portal.

3. **Select a Help Topic**
   - From the available options, choose the **Help Topic** that best categorizes your IT-related issue.

4. **Provide Ticket Details**
   - **Subject:** Enter a concise and descriptive outline of the issue.
   - **Description:** Detail the IT-related problem you are experiencing, formatting the information clearly as if composing an email.

5. **Create Multiple Tickets (Optional)**
   - Repeat the above steps to create additional tickets.
   - Ensure each ticket addresses a different type of problem to simulate a variety of real-world scenarios.

6. **Review and Submit**
   - Review the entered information for accuracy and completeness.
   - Click **Submit** to send the ticket request to the support team.

<p>
<img src="https://i.imgur.com/kTlhwFo.png" height="80%" width="80%" alt="Ticket Steps"/>
<img src="https://i.imgur.com/RlHNrkW.png" height="80%" width="80%" alt="Ticket Steps"/>
<img src="https://i.imgur.com/ApsciFm.png" height="80%" width="80%" alt="Ticket Steps"/>
</p>

**Processing Tickets as an Admin in osTicket**

From the perspective of an admin, managing ticket requests involves several key actions to ensure efficient resolution within established Service Level Agreements (SLAs). Follow the steps below to handle tickets effectively:

### **Steps:**

1. **Receive Ticket Requests**
   - **Access the Admin Panel:**
     - Log in to the **Admin Panel** of osTicket using your administrator credentials.
   - **View Incoming Tickets:**
     - Once logged in, navigate to the **Tickets** section to view all incoming ticket requests submitted by users.

2. **Reassign Tickets to Appropriate Agents or Teams**
   - **Review Ticket Details:**
     - Open each ticket to examine the details and understand the nature of the issue.
   - **Assign to Agents or Teams:**
     - Based on the issue category or required expertise, reassign the ticket to the most suitable agent or support team.
     - To reassign, select the ticket, choose the **Assign** option, and select the desired agent or team from the dropdown menu.

3. **Determine and Assign Severity Levels**
   - **Assess Issue Severity:**
     - Evaluate the impact and urgency of the issue to determine its severity level (e.g., SEV-A, SEV-B, SEV-C).
   - **Assign Severity Level:**
     - Update the ticket's severity level to ensure it aligns with the appropriate SLA for resolution.
     - To assign severity, edit the ticket details and select the corresponding severity level from the **Severity** dropdown.

4. **Ensure Compliance with SLAs**
   - **Monitor Resolution Times:**
     - Track the progress of each ticket to ensure it is resolved within the timeframes defined by its severity level.
   - **Escalate if Necessary:**
     - If a ticket is approaching its SLA deadline without resolution, escalate it to a higher priority or involve additional resources as needed.

5. **Example Scenario: Assigning a Ticket**
   - **Jane's Action:**
     - Admin **Jane** reviewed an incoming ticket and identified it as a critical issue.
     - She assigned the ticket to the **System Administrators** team.
     - Jane updated the ticket's severity level to **Emergency (SEV-A)** to prioritize its resolution within the 1-hour SLA.

<p>
<img src="https://i.imgur.com/8J4gYRr.png" height="80%" width="80%" alt="Ticket Steps"/>
<img src="https://i.imgur.com/COfD3VN.png" height="80%" width="80%" alt="Ticket Steps"/>
</p>


**Resolving Tickets in osTicket**

Effective ticket resolution in osTicket involves strong communication, proper ticket assignment, and thorough documentation to ensure a successful support environment. Follow the steps below to manage and resolve tickets efficiently:

### **Steps:**

1. **Maintain Strong Communication**
   - **Internal Communication:**
     - Collaborate with team members to discuss and address the issues outlined in each ticket.
   - **User Communication:**
     - Keep affected users informed about the status and progress of their tickets through regular updates.

2. **Assign Tickets Appropriately**
   - **Categorize Issues:**
     - Assess the nature and severity of each ticket to determine the appropriate team or individual for resolution.
   - **Delegate Tasks:**
     - Assign tickets to the relevant personnel, ensuring that each issue is handled by someone with the necessary expertise. For example, Jane may assign a ticket to John or manage it herself if suitable.

3. **Manage and Resolve Tickets Efficiently**
   - **Individual Resolution:**
     - Allow agents like Jane to independently manage and resolve tickets when possible, enhancing efficiency.
   - **Team Collaboration:**
     - For more complex issues, facilitate collaboration among team members to ensure comprehensive solutions.

4. **Ensure Comprehensive Documentation**
   - **Record Details:**
     - Document all aspects of each ticket, including the issue description, steps taken to resolve it, and the final outcome.
   - **Create References:**
     - Maintain detailed records to serve as references for handling similar issues in the future, promoting consistency and effectiveness.

<p>
<img src="https://i.imgur.com/Y1OaeVl.png" height="80%" width="80%" alt="Ticket Steps"/>
<img src="https://i.imgur.com/pU3kh02.png" height="80%" width="80%" alt="Ticket Steps"/>
<img src="https://i.imgur.com/YhXK7WL.png" height="80%" width="80%" alt="Ticket Steps"/>
</p>

<h2>Lessons Learned</h2>

Managing support tickets effectively requires adaptable protocols tailored to the specific work environment. Key insights gained from building and configuring osTicket include:

- **Variable Management Protocols:** Ticket management strategies can differ based on organizational needs, including setting quotas for the number of tickets resolved within designated time frames.
  
- **Prioritization of Issues:** Assigning priority levels to tickets ensures that critical issues are addressed promptly, enhancing overall support efficiency and user satisfaction.
  
- **Comprehensive Understanding of Ticket Systems:** Developing osTicket from scratch provided a deep understanding of ticket lifecycle management, enabling me to effectively handle and resolve IT support requests in a professional setting.

These lessons underscore the importance of flexibility, prioritization, and thorough system knowledge in maintaining a robust and responsive IT support environment.
