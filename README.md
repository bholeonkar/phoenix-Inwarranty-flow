# Postman API Automation Integratoin with github Action #

This repository is a demonstration for POC integrating test with github Actions. The test with are written in postman and they are executed on the VM with help of newman and newman-reporter--htmlextra.
Github Actions will trigger the project execution on every push to the main branch. along with that you can also execute the project manually under workflow_dispatch. The project runs on a schdule time with the help of
the cron job.

The HTML reports is archieved and kept in the artifact section for the team to download . along with that they can view the report .

the latest report is mailed to the team members

## Tech stack ##

1. Postman
2. Node Js 22
3. Newman
4. Newman-reporter-htmlextra
5. Github Actions
6. Gmail SMTP
7. Github pages
8. CSV for data driven testing
9. AWS EC2 instance for Self hosted github runner.

