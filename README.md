# Valentine's Project

## Overview
This project involves the creation and automation of personalized Valentine’s cards for over 200 recipients. It includes design, development, and automation processes such as automating GitHub accounts for code layers, designing cards using Figma, converting designs to code, and automating email sending.

## Table of Contents
- [Project Structure](#project-structure)
- [Design](#design)
  - [Figma Design](#figma-design)
  - [HTML, CSS, and JS Implementation](#html-css-and-js-implementation)
- [Automation](#automation)
  - [GitHub Account Automation](#github-account-automation)
  - [Email Automation](#email-automation)
- [Setup](#setup)
- [Usage](#usage)


## Project Structure
```
valentines-project/
│
├── design/
│   ├── figma-design/
│   └── card-templates/
│
├── src/
│   ├── css/
│   ├── html/
│   └── js/
│
├── automation/
│   ├── github-accounts/
│   └── email-scripts/
│
├── README.md
└── LICENSE
```

## Design

### Figma Design
The card design was initially created using Figma, allowing for a collaborative and iterative design process. The finalized designs are stored in the `design/figma-design/` directory.

### HTML, CSS, and JS Implementation
The designs were then converted into responsive and interactive cards using HTML, CSS, and JavaScript. The source code for these implementations is located in the `src/` directory:
- **HTML**: Provides the structure of the card.
- **CSS**: Ensures the card is visually appealing and responsive.
- **JavaScript**: Adds interactive elements and dynamic content.

## Automation

### GitHub Account Automation
Automating the creation and management of GitHub accounts to handle layers of code was accomplished using custom scripts. These scripts can be found in the `automation/github-accounts/` directory.

### Email Automation
To send out the personalized Valentine’s cards, email automation scripts were developed. These scripts automate the process of customizing and sending emails to all 200 recipients. The scripts are located in the `automation/email-scripts/` directory.

## Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/valentines-project.git
   cd valentines-project
   ```

2. **Install dependencies** (if applicable):
   ```bash
   npm install
   ```

3. **Set up environment variables** (if applicable) for email automation:
   ```bash
   cp .env.example .env
   ```
   Fill in the `.env` file with your email service credentials and other necessary details.

## Usage
1. **Run the automation scripts**:
   - GitHub account automation:
     ```bash
     python automation/github-accounts/automate_github.py
     ```
   - Email automation:
     ```bash
     python automation/email-scripts/send_emails.py
     ```

2. **Serve the HTML, CSS, and JS files**:
   Use any local server tool like `http-server` to serve your static files.



Feel free to adjust any details or add additional information as needed.
