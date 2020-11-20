# Camunda BPM 
## Project Name - Onboarding-bpm

### How to create a new Camunda SpringBoot Project
https://start.camunda.com

### You would need a modeler
https://camunda.com/download/modeler/


Application runs at - 
http://localhost:8080/

Credentials to login -
Username - demo
Password - demo

Major components to look at -
Cockpit - This is the admin console.
TaskList - Where various tasks can be seen.

Rest Endpoints - 

{{host8080}}/engine-rest/deployment/create

{{host8080}}/engine-rest/process-definition/key/New-Hire-Success/start

{{host8080}}/engine-rest/task?processDefinitionKey={{processId}}

{{host8080}}/engine-rest/task/{{taskId}}/complete

'''json
{
    "variables": {
        "accessGranted": {
            "value": "Yes"
        }
    }
}
'''



