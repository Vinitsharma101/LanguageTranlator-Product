# Translator Web App

This web application allows you to translate text from one language to another using the Microsoft Translator API. It's built with React and Material-UI for the frontend, and Axios for handling API requests.

## Table of Contents

- [Features](#features)
- [Setup](#setup)
  - [Clone the Repository](#clone-the-repository)
  - [Install Dependencies](#install-dependencies)
  - [Set Up Environment Variables](#set-up-environment-variables)
  - [Start the Development Server](#start-the-development-server)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Translate text between various languages supported by Microsoft Translator API.
- Auto-detect language feature to automatically identify the language of the input text.
- User-friendly interface with Material-UI components for easy navigation and interaction.

## Setup
🔹 How Users Can Use the Web App:
Create Azure Account

Go to https://azure.microsoft.com/free

Sign up for a free account.

Create Translator Resource

In Azure Portal, search for “Translator”

Click Create, choose region, pricing tier (F0 for free), and resource group.

After creation, go to the resource → Keys and Endpoint

Copy API Key & Region

You’ll get:

Key1 or Key2 (use either)

Region (e.g., centralindia, eastus)

Use in Web App

Paste the key and region into the app (either in UI or .env file depending on setup).

Example in code:

js
Copy
Edit
headers: {
  'Ocp-Apim-Subscription-Key': '<your-key>',
  'Ocp-Apim-Subscription-Region': '<your-region>',
  'Content-Type': 'application/json'
}
Start Translating

Enter text

Select input & output languages

Click translate → see results instantly



To run this project locally, you need to have Node.js and npm (or yarn) installed on your machine.

### Clone the Repository

```bash
git clone <repository-url>
cd translatorApp

