# AcuCafe Tech Lead Assessment

During this assessment, you will have the opportunity to demonstrate your expertise in reviewing code, providing feedback, and addressing scalability, maintainability, and stability concerns in a real-world scenario. 

## Project Overview

You are tasked with evaluating a portion of our AcuCafe system, which integrates with the drink dispensing system in our stores. This system processes customer requests and prepares drinks accordingly. It's important to note that occasionally, the AcuCafe system may output incorrect orders (Such as allowing milk to be added to Ice Tea), which our baristas manually review and correct when necessary. 

In two years, AcuCafe is expected to expand to 50,000 stores globally, where it will handle hundreds of orders per minute. Additionally, it will offer thousands of potential drink variations and customization options beyond just Sugar and Milk. Your task is to ensure that our codebase is robust enough to meet these future requirements while maintaining the ability to release new features. 

## Assessment Overview

### Requirements

The project consists of an ASP.NET Core API, and an Angular 10 front-end. You’ll need the following on your computer to run this: 

* Visual Studio 2022 or Visual Studio Code 
* .NET 6 SDK 
* Node 14 

Running the project from Visual Studio will also start the angular app and open up a browser window. Running up locally will allow you to see the current state of the UI.  

The assessment consists of two parts:

### Part 1 - Code Review and Feedback (20 mins)

Imagine you are reviewing a pull request from an engineer for a portion of our AcuCafe project. Your task is to identify issues, suggest improvements, and provide feedback on both the front-end and back-end aspects. Assume this code is part of a larger order management system and they have been given the following Figma file for Designs: [Design Link](https://www.figma.com/file/oqGXgrX6769HUXv37t5tFM/Front-End-AcuCafe?type=design&node-id=5%3A7152&mode=design&t=BfIFApCwtCF7UJkM-1)

### Part 2 - Scalability and System Improvement (40 mins)

In this part, we will have a discussion of how you would address scalability, maintainability, and stability issues in AcuCafe, considering its goals for the next two years. These questions may not necessarily relate to the specific part of the project shown in the repository you reviewed in Part 1.  
