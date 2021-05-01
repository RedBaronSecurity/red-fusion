# Red-Fusion 
## Table of Contents
  - [What is Red-Fusion?](#what-is-red-fusion)
    - [General](#general)
  - [How does it look?](#how-does-it-look)
      - [Overview](#overview)
      - [Client and Server](#client-and-server)
## What is Red-Fusion?
### General
Red fusion is a platforom for simplifying and easely managing multiple scanning applications (*OWASP Zap*, *Detectify* etc.) while optionally creating issues for Jira and adding communicating with it for when they are done.

## How does it look?
#### Overview
We want to make Red-Fusion an Electron based **Desktop Application** and also a **Web Application** for easely checking the status of the scans while not next to your machine. 

#### Client and Server
The application is meant to have a server running (it can be a local machine or somewhere in cloud --this is a similar approach to Atlassian-- ). 

After the initial configuration the cliend could connect with a username and password to the UI.The user has the option to configure the scanning applications. The user can then start/ stop or schedule scans. 
