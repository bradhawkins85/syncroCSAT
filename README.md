# syncroCSAT
Generate a Microsoft Customer Voice CSAT Survey for Syncro Tickets

The Power Automate ZIP contains the flow to search Syncro tickets that have the Status of CSAT Survey.
The flow triggers every 4 hours and generates a Customer Voice invitation that is attached to the respective ticket, the ticket is then marked as resolved.

You need to update the SyncroDomain and SyncroAPIKey variables in the first 2 steps, as well as the Project, Survey and Company Name in the Create Invitation step.

This is still a work in progress, currently the flow does not handle tickets assigned to companies but needs a contact attached to the ticket as well regardless of the company having an email address.
This flow has had limited testing, use at your own risk.
