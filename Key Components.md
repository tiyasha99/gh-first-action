## Key Components of Github actions ##

* Workflows 
* Jobs
* Steps


### Workflows
You can have multiple workflows when setting up a repository. This is the first step we take when setting up automations with github actions. 

Workflows that are attached to a github repo contain one or more jobs which are triggered upon _Events_. This events define when a workflow will be executed. For example, you could add an event that requires manul activation of a workflow, or an event may be a commit, so with each commit a workflow is triggered.

### Jobs

Each workflow will have jobs.
Jobs are then the things inside of the events that contain certain steps that will be executed. Each job defines a so-called Runner which is simply the execution environment, the machine and operating system that will be used for executing these steps. With GitHub ACtions these runners can ither be runners that are predefined by GitHub.GitHub offers runners for Linux, Mac Os and Windows and we can also configure runners of our own.

These Jobs then also define the steps that will be executed in this runner environment (On that machine you specified). You can have one or multiple jobs in a workflow. If you have multiple jobs, they run in parallel by default, but we can configure them to run in sequential order as well. You can also define certain jobs that would only be run if a certain condition is met.

### Steps

Each jobs has startain steps that will be executed in the order that they are specified

 Now the part where the actual work happens is the steps. Steps belong to jobs and a job can have one or more steps. A step is either a shell script or an Action. Basically Actions in the context of GitHub actions are predefined scripts that perform a certain task. We can create custom actions or use a third party action. Each job must have atleast one step. Steps are sequentially executed and can also be conditional.
