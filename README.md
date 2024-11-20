This message flow provides real-time weather alerts via an email based on set location.

Features

-Integrates with Weather API and sends an alert every day at 5am using a Scheduler node.

-Uses an email to send alerts

To test the flow without using the scheduler node, wire the flow as shown in the diagram.
![Trigger using HTTPInput Node](https://github.com/user-attachments/assets/6cf9f37d-c1b8-4490-becd-fe31e41db602)

NB:

You will need to populate the recipient and sender email address as well as SMTP Server and Port on the email output node properties
