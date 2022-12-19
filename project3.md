# **MERN STACK IMPLEMENTATION**

We are going to create a **To-do application** that creates a to-do list

## **STEP 1 –** We will start with the **BACKEND CONFIGURATION** *(Installing Node.Js, Express.Js, and Mongodb)*

The first thing to do is to update and upgrade the linux package repository with the following commands below:

`sudo apt update`

`sudo apt upgrade`

Next is to get the location of Node.js software from

`curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -`

Install Node.js on the server with the command below

`sudo apt-get install -y nodejs`

**Note:** The command above installs both nodejs and npm. **NPM** is a package manager for Node like **apt** for Ubuntu, it is used to install Node modules & packages and to manage dependency conflicts.

Verify the node installation with the command below:

`node -v `

Verify the package manager installation with the command below:

`npm -v` 

## **Application Code Setup**

Create a new directory for your To-Do project:

`mkdir Todo`

Run the command below to verify that the Todo directory is created with ls command
`ls`

Now change your current directory to the newly created one:

`cd Todo`

Next, you will use the command 

`npm init`

This command is to initialise your project, so that a new file named **package.json** will be created. This file will contain information about your application and the dependencies that it needs to run. Follow the prompts after running the command. You can press **Enter** several times to accept default values, then accept to write out the package.json file by typing **yes.**

![Image](./Images/hdjshs.png)

Run the command `ls` to be sure that you have package.json file created.

## **Installing ExpressJs**

Before we proceed to installing ExpressJ.s, have it at the back of your mind that Express is a framework for Node.js, therefore a lot of things developers would have programmed is already taken care of out of the box. Therefore, it simplifies development, and abstracts a lot of low-level details. *For example, Express helps to define routes of your application based on HTTP methods and URLs.*

To use express, install it using npm:

`npm install express`













