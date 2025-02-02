# CSC/ECE 517 Ruby on Rails: Online Shopping System

## Description

We will be implementing a simple online shopping portal where registered users can view and purchase products. This project will not focus on basic data validations or edge cases. Instead, it will focus on implementing different functionalities and introducing different concepts which will help in your projects. The general strategy for RoR frontend is to create classes with the scaffold, and then link them together by implementing associations. The difference between Typescript(TS) frontend and RoR frontend is that TS is not an MVC, and has a separate front end which communicates to the Ruby on Rails API backend. The functionalities are limited but the scope of learning will be broader.

## Functionalities

The simple online shopping system that we will build will have the following features. The user will be able to:

1. Register for the shopping website  
2. Create sessions by login and logout  
3. Purchase multiple items  
4. View their purchase history till date  
5. Will not be able to view pages that they aren’t authorized to view

## Prerequisite Software

1. Docker Desktop, as it comes with Docker Engine and Docker Desktop.  
2. RubyMine (recommended) or your preferred editor (VSCode works perfectly too)  
   1. You can also connect to VCL using VSCode which is more convenient option \- Refer to the instructions [here](https://docs.google.com/document/d/18rpqd8HbzB_aNOcRewKLLoWq5egkOxeLdvrVuC9UrG4/edit?tab=t.0) for setting up the same  
      To install RubyMine on Linux, e.g., if you are using Virtual Box, use  
      	sudo apt install snapd \-y  
      sudo snap install rubymine \--classic  
      rubymine  
      or see [this installation guide](https://www.jetbrains.com/help/ruby/installation-guide.html#standalone).   
3. Compatible versions of Ruby and Rails. Please check [this document](https://www.fastruby.io/blog/ruby/rails/versions/compatibility-table.html) to ensure compatibility between your Ruby version and Rails version.  
4. Git  
5. Node. [Download](https://nodejs.org/en) and install, if not already installed. Node is required for running the front end application. Follow the instructions on the official site for installing.   
   1. On Linux, If you run into issues saying that “nvm or fnm etc not found”, restart your terminal as the newly created environment variable-related changes would not reflect in the current bash session

---

Next Chapter: [Instructions](./docs/1.md)  
