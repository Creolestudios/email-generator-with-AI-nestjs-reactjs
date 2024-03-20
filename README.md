# email-generator-with-AI-nestjs-reactjs
This is the platform where the users just need to type in the text regarding which they want an email template to be generated. Users can type in the textbox in a layman language and the prompt defined would be picking up the context and based on the context, it would give the users a template fitted with the custom content. 



## AidumGenerator App (EmailGpt)

## Table of Contents

1. [Introduction](#1-introduction)
2. [Project Overview](#2-project-overview)
3. [Getting Started](#3-getting-started)
4. [Code Structure](#4-code-structure)
5. [Dependencies](#5-dependencies)
6. [Deployment](#7-deployment)
7. [Usage](#8-usage)


## 1. Introduction

Welcome to our innovative email template generation platform! Our platform aims to simplify the process of creating email templates by allowing users to input their content in plain language. By leveraging natural language processing (NLP) technology, our platform interprets the user's input and identifies key elements to generate a template that suits the purpose of their message. Whether it's a business proposal, a marketing campaign, or a simple newsletter, our platform ensures that users can quickly generate professional-looking email templates without any technical expertise.



## 2. Project Overview

In this documentation, we will explore how to use our platform, including its features, functionalities, and integration options. Whether you're a business owner, marketer, or developer, our platform offers a user-friendly solution for creating compelling email templates in minutes. Let's dive in and revolutionize the way you craft emails!

## 3. Getting Started

To get started with the TranscriptGpt App, follow these steps:

### Prerequisites

Make sure you have the following installed:

- A modern web browser (e.g., Chrome, Firefox, Safari)
- An internet connection (for fetching external dependencies)
- Insatll Node.js [See this](https://www.guru99.com/download-install-node-js.html) for installation steps.
- Install MongoDB [See this](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/) for installation steps.

### Installation

1. **Clone the Repository:**

   ```bash
   git clone git@github.com:Creolestudios/email-generator-with-AI-nestjs-reactjs.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd email-generator-with-AI-nestjs-reactjs
   ```

3. **Client and Server Setup**

   * Create and Add credentials in development.env file in Server/src/common/env

   ```
    PORT=7001
    BASE_URL=http://localhost:
    OPEN_AI_KEY=
    UNSPLASH_ACCESS_KEY=
    SERVER_URL=
    DB_HOST=localhost
    DB_PORT=27017
    DB_USERNAME=
    DB_PASSWORD=
    DB_DATABASE=
    TEMPLATE_PATH=/public/templates
    IMAGE_PATH=/public/images

   ```

   ## Client Setup

   ```
   npm install 

   npm start 

   ```


   ## Server Setup


   ```
   npm install 

   npm run start:dev

   ```




## 4. Code Structure

The project follows a modular and organized structure to enhance readability, maintainability, and scalability. Key components include:

- **ReactJs** The main structure of the web page designed using React Framework.
- **NodeJs** Backend Logic written in nodejs, Logic for handling user interactions, getting transcript , and giving summary as Situations, Challenges, Risks, Impacts and Solutions.
- **unsplash** get images based on prompts from unsplash. 
- **OpenAI** Using OpenAI api key to get summary of Situations, Challenges, Risks, Impacts and Solutions from transcript.

## 5. Dependencies

- **MongoDB** NoSQL based database for efficient storage of data  
- **OpenAI** Provides different text based models like gpt-3.5,gpt-4,text-ada-embedding



## 6. Deployment

The EmailGPT App is deployed and accessible online. You can use the following link to access the application: [EmailGpt](https://www.creole.tech/emailgpt/)

## 7. Usage

1. **Adding a Prompt:**
   - Add Prompt manually to generate email template for

2. **Apply filter:**
   - select filter based on choice you want to generate email template for.

3. **Select Images:**
   - Select Available images from tab which pop ups what clicked on images .

4. **Download Template:**
   - Click the "Download" button to download template.

5. **Generate Different Response:**
   - Click the "Try Again" to generate different response.

