# Chat history emailer

Code to automatically send an email with the history of your chat with Watson Assistant. What it does is maintain a history of the messages sent to and from your Watson assistant. When you minimise the chat window the user will be prompted to enter an email address where the history should be sent (if you cancel no email will be sent).

## Deployment

1. Place the code contained in the history_template.html file somewhere in the header part of your web site's page
2. Modify the INTEGRATION_ID, REGION_ID and INSTANCE_ID variables to match your Watson Assistant instance
3. Create an account on elasticmail.com if you don't already have one. Then insert the SMTP_HOST, SMTP_USERNAME, SMTP_PASSWORD and FROM_ADDRESS in the javascript code
