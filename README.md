<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

## osTicket - Intake Through Resolution ##
> This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket. In this demo, we will be creating tickets as end users. Observing the main ticket properties and responding to them as help desk professionals.
 - 🔗 Admin & Agent Login Page: `http://localhost/osTicket/scp/login.php`
 - 🔗 End User's osTicket Page: `http://localhost/osTicket`
 - 🗒️ Video demo shows all ticket lifecycles.  <br />
---

## Video Demonstration ##
### [<img src="https://img.icons8.com/?size=100&id=19318&format=png&color=000000" align="center" width="40" height="40">](https://www.youtube.com/channel/UC9YvuJxKB94ByhwCfZQ_5Kg) [osTicket Post Install Configuration](https://youtu.be/7HAPxk8Glic)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 </b>

<h2>Ticket Lifecycle Stages</h2>

- Intake 🎟️
- Assignment and Communication 🎛️
- Working the Issue 👷
---

<h2>Lifecycle Stages</h2>

<img src="https://github.com/user-attachments/assets/50b9c74e-b39e-475e-b230-e8c77e69474a" /> <br />

1️⃣ Intake ⤵️
- As an end-user, create the following tickets:
> - Ticket 1: entire mobile/online banking system is down.
> - Ticket 2: accounting department needs adobe upgrade, broken.
> - Ticket 3: CFO’s laptop will no longer turn on.
> - Ticket 4: Karen forgot her password
---

<img src="https://github.com/user-attachments/assets/d92b5db3-cf2b-4066-8aef-83065d63b092" /> <br />
<img src="https://github.com/user-attachments/assets/9a468cd5-7fc8-47b2-8036-a8ba74108b8f" /> <br />

2️⃣ Assignment and Communication ⤵️
- Set Basic Properties to all tickets:
> - Ticket 1: `Sev-A` (1 hour, 24/7), `SysAdmin`
> - Ticket 2: `Sev-C` (4 hours, 24/7), `Support`
> - Ticket 3: `Sev-B` (Business Hours), `Support`
> - Ticket 4: `Sev-B` (4 hours, 24/7), `Support` 
- Assign and Observe Agent Permissions:
> - Switch to `Admin panel` and assign **Jenny Doe** Extended Access to `Sys Admins` department with `View Only` access.
> - Log in as **Jenny Doe** and observe the escalated ticket in view only access.
> - Log in as **Johnny Doe** and observe ticket becomes inaccessible.
---

<img src="https://github.com/user-attachments/assets/edce1b88-f744-491d-8bed-b8913de96cce" />
<img src="https://github.com/user-attachments/assets/c94bf4a4-eab1-4004-87a9-837837d14a15" /> <br />

3️⃣ Working the Issue ⤵️
- Solve all of the tickets:
> - Ticket 1: As a Help Desk Agent **AdminUser**, observe the ticket’s properties:
    > - `Department`, `SLA`, `Assigned To`. Work the ticket to completion as **AdminUser**.
> - Ticket 2: As a Help Desk Agent **Jenny**, observe the ticket’s properties:
    > - `Department`, `SLA`, `Assigned To`. Work the ticket to completion as **Jenny**.
> - Ticket 3: As a Help Desk Agent **Johnny**, observe the ticket’s properties:
    > - `Department`, `SLA`, `Assigned To`. Work the ticket to completion as **Johnny**.
> - Ticket 4: As a Help Desk Agent **Johnny**, observe and assign the ticket’s properties:
    > - `Department`, `SLA`, `Assigned To`. Work the ticket to completion as **Jenny**.
---

