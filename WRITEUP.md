# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

_For **both** a VM or App Service solution for the CMS app:_

- _Analyze costs, scalability, availability, and workflow_
- _Choose the appropriate solution (VM or App Service) for deploying the app_
- _Justify your choice_
  \*\*\* Virtual Machine

* Advantages:
  – It allows we have full access and control the VM
  – Unnecessary to purchase hardware
  – Support of both Linux and Windows OS
  – We have multiple types and sizes to choose depend on demand with varying amounts of CPUs, RAM and storage
  – High availability and scaling
* Limitations:
  – Much more expensive
  – Need much time to consume for developer to configure, update and maintain...

\*\*\* App Service

- Advantages:
  – Support multiples programming languages such as Python, C#, Java, Nodejs, PHP, Ruby
  – Quickly Create and deploy web app or backend mobile
  – High availability and auto-scaling and support both Linux and Windows environments
  – Vertical or Horizontal scaling
  – Support CD (Continuous Deployment)
- Limitations:
  – Limited about list of programming languages
  – Hardware limitation (maxmimum is 14GB RAM and 4 CPU cores per instance)
  – Always pays for service plan even if application is not running
  – Limited access to host server

==>> With cost constraints and acceptable hardware, I choose App Service. Because it is not necessary to spend a lot of time creating a VMs, then configure and update

### Assess app changes that would change your decision.

_Detail how the app and any other needs would have to change for you to change your decision in the last section._
\*\*\* To change my decision:
– Increase the number of users
– This app is a lightweight application. If this app exceeds the App Services limit configuration (more than 14GB RAM and 4 CPU cores per instance), I will think about a VM for this case
– I would like to control Infrastructure such as configuration, upgrade...
– I need a VM because of security reasons

\*\*\* URL to test my App Service:

<!-- https://tungtt44-project1-webapp.azurewebsites.net/ -->
