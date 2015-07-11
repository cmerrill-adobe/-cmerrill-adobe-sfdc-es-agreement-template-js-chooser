# sfdc-es-agreement-template-js-chooser

This button simplifies the buttons for EchoSign for Salesforce.com.

The button will drop in to typical standard objects via copy and paste. No changes are needed for the following objects:
Account
Contact
User
Opportunity
Contract
Case
Lead

The button gets the object keyPrefix from the id in the URL. 
That is then used to determine the object API name to find the related agreement templates.

The user is then presented with a popup window showing all related agreement templates.

If there is only one template, then that template is used and no popup is shown.

if there are no templates, then an alert dialog is shown
