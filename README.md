<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This guide walks through the ticket lifecycle in the open-source help desk system osTicket, from submission to resolution.

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

<img width="763" height="447" alt="Screenshot 2026-02-18 123703" src="https://github.com/user-attachments/assets/aa8f3f08-53e3-48c2-85ad-9788a356890f" />

<img width="761" height="886" alt="Screenshot 2026-02-18 124402" src="https://github.com/user-attachments/assets/06de022c-8713-4a39-b76b-b92ff75b3510" />

Ken, a customer, is submitting a new ticket under the Personal Computer Issues help topic. He reports that some people in the accounting department can't use adobe reader.

<img width="883" height="345" alt="Screenshot 2026-02-18 124433" src="https://github.com/user-attachments/assets/c151e631-b104-4b30-acb8-65c382c6d80e" />

Agents can access and manage active tickets through the Agen Panel, while queue managers allocate priority tickets to the appropriate agents and ensure that the relevant SLAs are followed.

<img width="868" height="716" alt="Screenshot 2026-02-18 125232" src="https://github.com/user-attachments/assets/3cb929c3-af3d-4d99-8370-b3df098c6698" />

In this example, the ticket's priority is marked as High because of its potential impact on Personal Computer Issues. The SLA has been updated to Sev-B since there is an ongoing audit that requires Adobe Reader. The ticket is assigned to John, the help desk agent responsible for end-user support within this area. In some ticketing systems, customers may have the option to select their own SLA plans.

<img width="868" height="575" alt="Screenshot 2026-02-18 125612" src="https://github.com/user-attachments/assets/4295d033-6929-4614-aed3-4e8580567edb" />

<img width="885" height="449" alt="Screenshot 2026-02-18 125658" src="https://github.com/user-attachments/assets/62766020-74e2-46dc-a771-06e7ffbf3246" />

The ticket was resolved after identifying the root cause as the Adobe Reader package deployed last night. Users can either wait ~1 hour for the updated package or manually install it from the software catalog. An internal note was added to inform Ken that the root cause analysis is complete, solution successfully delivered.
