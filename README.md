# AI-Enhanced Incident Response Automation on Azure

<br>


This project introduces a ChatGPT solution on Azure, crafted to elevate cybersecurity incident management. Dive into the Logic App Designer configuration, role assignments, playbook execution, and the generation of context-aware comments by ChatGPT during incident responses. The seamless integration of AI into the SIEM system ensures efficient cybersecurity operations and contributes to enhanced incident resolution through automatically generated comments.

<br>
<br>


### Prerequisites:

Before you begin with this project, ensure that you have the following in place:

- **Azure Account**:
Create or use an existing Azure Cloud account.

- **Azure ChatGPT API Key:**
Obtain an API key for ChatGPT from the OpenAI platform. This is necessary for integrating ChatGPT into the incident response workflow.

- **Security Information and Event Management (SIEM) System:**
Have a SIEM system deployed in your Azure environment. This project is designed to integrate with a SIEM system for efficient cybersecurity operations.

- **Azure Resource Group:**
Create an Azure Resource Group to organize and manage the resources deployed during the project.

- **OpenAI Account:**
Create an account on the OpenAI platform to obtain the necessary API key for accessing ChatGPT.

<br>


### Configuration Snapshots:

#### **Crafting a Playbook:**
- Develop a tailored playbook outlining precise steps for incident response actions.

![Imgur](https://i.imgur.com/hfUb3y5.jpg)

<br><hr>

#### **Designing the Workflow with Logic App:**
- Explore the Logic App Designer to visually configure the workflow, specifying triggers, actions, and conditional logic for incident automation.

![Imgur](https://i.imgur.com/D5AKfdN.jpg)
![Imgur](https://i.imgur.com/AYjABTh.jpg)
![Imgur](https://i.imgur.com/CrX1sxv.jpg)

<br><hr>

#### **Role Assignment for Logic App:**
- Ensure the Logic App has the necessary permissions by assigning appropriate roles, enabling it to perform actions securely

![Imgur](https://i.imgur.com/MTkriI3.jpg)

<br><hr>

#### **Manual Execution of Playbook on Incident:**
- Validate incident response actions by manually running the playbook on a specific incident.
  
![Imgur](https://i.imgur.com/sOzDKBg.jpg)

<br><hr>

#### **ChatGPT-Generated Comments:**
- Witness the results of ChatGPT integration as it autonomously generates context-aware comments during incident responses.

![Imgur](https://i.imgur.com/gyzKMTP.jpg)

<br><hr>

#### **Creating an Automation Rule:**
- Establish an automation rule defining the conditions under which the incident response automation, including ChatGPT comments, should be triggered.

![Imgur](https://i.imgur.com/r6I0fU7.jpg)

<br><hr>

#### **Automated Comment Generation on Incident Occurrence:**
- Experience the seamless generation of comments by ChatGPT when the defined automation rule criteria are met during an incident.

![Imgur](https://i.imgur.com/dPR06FR.jpg)
