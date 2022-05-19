# SMDG Terminal Code List

Example GitHub Repository, for testing the SMDG Wehook and Github Actions

## Actions

* Clean Cities - For consistency we want to see all city names in the title case i.e. `ABU DHABI` whould become `Abu Dhabi`
* Publish to the Website - Publish the Excel version of the code list to the website from the github repository
* Deploy the API - Push the codes into the shared BIC and SMDG Facility code API

## Webhook

The webhook will send changes to the AWS Infrastructure to trigger updates and pull the SMDG codes into the Dynamo DB which will combine the SMDG codes with the BIC codes for common delivery via API to industry.
