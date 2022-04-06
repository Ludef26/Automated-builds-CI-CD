# Automated Builds CI / CD

## Automated Builds

In any build of software process, there are different parts, from generating code, compiling files and compressing them, generating installers, creating realeases... The use of different automation tools such as CI and CD constitute what is called DevOps. This process allows us to increase the quality of the final product without any type of human intervention and guaranteeing its safety.

![](https://github.com/Ludef26/Automated-builds-CI-CD/blob/main/Docs/Images/CI-CD.png)

## What is CI?

CI means continuous integration and this name is given to the set of processes of building, testing and merging the different changes that occur in a code over the course of one or several days.

By doing all these processes automatically thanks to tools like Github Actions, the developer has the guarantee that his code will be built in a safe way and he will have time to invest in other more important processes of his project.

## What is CD? 

CD stands for continuous delivery and is totally linked to continuous integration. This allows us to be able to make realeases of our project whenever we want in an automatic way, without having to worry about whether it has been uploaded correctly or has been done in the correct format. It will work as soon as you get the notification from continuous integration that everything is ok.

Here we have a diagram where it tells us which parts each process includes.

![](https://github.com/Ludef26/Automated-builds-CI-CD/blob/main/Docs/Images/Ci-CD-process.png)

## Why use CI / CD

There are several reasons to use CI and CD tools, here are some of them:

* Improve the efficiency.

* Do not spend time on these automatic processes.

* Ensure that the product is uploaded correctly.

* Minimize tasks.

* Have an ordered history of the releases made to correct any errors.

## Guide of github action

### Workflows

Developers can use different workflows depending on their needs. For example, whenever there is an error, an issue will have to be made, this issue will be assigned to a contributor to fix it, when it is fixed they should make a pull request and check that everything is correct. But this is where Github Actions and its workflows come in, since they allow us to do some of these processes automatically without needing our attention, such as checking if the bug has been fixed.

### Jobs 

Jobs are the first thing described in a workflow, they can work in parallel or sequentially, depending on whether we establish a job order.

### Steps 

The steps are the last element of the workflows and are inside the jobs. Inside are the actions and commands, this is where we can modify exactly what we want our workflow to do.

![](https://github.com/Ludef26/Automated-builds-CI-CD/blob/main/Docs/Images/Github-Actions.png)
