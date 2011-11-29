Setup
-----

You can configure the module from the module page. The default role preselects a role from the roles drop down when sending an email. The email template file will let you use a template for you email message - set a php file relative to your templates directory with the variables $body and $subject within it.

Usage
-----

Go to 'Mailer' in the main menu in the backend. Choose a role to send the email to. You email will be sent to all the users within that role. You can optionally send a test transmission by entering an email address in the last field - in this case the transmission will be sent to that address.

Planned features
----------------

- Multipart email messages
- Archiving of previously sent messages and draft messages (campaigns)
- Spport for images within the email body
