---
title: "IU Alumni System Documentation"
keywords: alumni system, university, documentation
tags: [overview, getting_started, user_guide, developer_documentation, how_to, faq]
sidebar: mydoc_sidebar
permalink: index.html
summary: Welcome to the IU Alumni System Documentation. Whether you're a student, alumnus, university staff, or developer, this comprehensive guide will assist you in navigating and utilizing the system.
---

# IU Alumni System Documentation

## Home
Welcome to the IU Alumni System documentation. Here you will find all you need to navigate and utilize the system, whether you are a student, alumnus, university staff, or a developer.

## Overview
The IU Alumni System is a comprehensive platform that enables Innopolis University alumni to stay connected with the university. Through this portal, alumni can register for elective courses, manage event attendance, and request access passes to the university. This interactive system aims to provide a seamless experience for users while maintaining a robust and secure backend for administrators.

## Getting Started
This section guides you through the initial steps to get the IU Alumni System up and running on your local machine.

### Prerequisites
Before you begin, ensure you have the following installed on your system:
- Python 3.8 or higher
- pip (Python package installer)
- Node.js 12 or higher
- npm (Node package manager)
- Docker
- PostgreSQL

These are required to run the backend and frontend of the system as well as for database management.

### Installation Guide
To install the IU Alumni System, you need to set up both the backend and frontend parts of the application.

#### Backend Installation
1. Clone the repository to your local machine.
2. Navigate to the `app` directory in your terminal.
3. Set up a virtual environment using `python -m venv venv`.
4. Activate the virtual environment with `source venv/bin/activate` (on Unix systems) or `venv\Scripts\activate` (on Windows).
5. Install the required packages using `pip install -r requirements.txt`.

#### Frontend Installation
1. Navigate to the `src` directory in your terminal.
2. Install the required Node.js packages using `npm install`.
3. Build the project for production with `npm run build`.

### Initial Configuration
Once the installation is complete, some initial configuration might be necessary:

#### Backend Configuration
1. Ensure that PostgreSQL is running on your system.
2. Create a new database for the application.
3. Configure the database settings in `config.py` to connect to your new database.

#### Frontend Configuration
1. Set up the environment variables required for the frontend application in `next.config.js`.
2. Ensure the backend API is accessible from the frontend application.

Now your IU Alumni System should be ready for use or development purposes.

## User Guide

This section provides guidance on how to use the IU Alumni System. Follow these instructions to navigate through the system and utilize its features.

### 1. Login

![Login Page](media/login.png)

To access the IU Alumni System, start at the login page. If you don't have an account, you can register for one. Otherwise, enter your email address and password, then click `Continue`. Alumni can also use the Innopolis University SSO for convenience.

### 2. Home Page with Overview

![Home Page](media/overview.png)

Once logged in, you're greeted with the home page. This provides an overview of the platform, including quick access to main features such as event updates, course registrations, and pass requests.

### 3. Request Pass

![Request Pass](media/requests_pass.png)

To visit the university, click on `Request Pass`. You'll need to enter the date of your visit and guest names if applicable. Note the general information about pass collection and the eligibility criteria.

### 4. Request Electives

![Request Electives](media/elective_request.png)

For enrolling in elective courses, go to `Request Elective`. You'll see a list of available courses along with instructor names and delivery modes. Click `Request` on the course you're interested in.

### 5. History of Elective Requests

![Elective History](media/elective_history.png)

The system maintains a history of your elective requests. You can review past submissions and their statuses (pending, approved, or rejected) under the history section.

### 6. Make Donations

![Donation Page](media/donation.png)

Contributions are valuable to the university community. Visit the `Make Donations` page to support various university causes and initiatives.

### 7. Manage Personal Account

![Account Management](media/account.png)

Your personal account section allows you to update your profile details and contact information. Keep your data up-to-date for better interaction with the alumni community.

### 8. Admin Section (New Login Required)

![Admin Section](media/admin.png)

For administrators, a separate login is required to access the admin panel, where you can manage user requests. The UI is intuitive, with options to approve or decline requests.

Remember to replace `path-to-your-screenshot-X` with the actual paths where you have stored your screenshots within your project repository.

For administrative tasks, it's important to securely manage alumni requests, ensuring that actions reflect the current policies and standards of the university.

Please note that the admin section requires a new login, reflecting the need for higher security and administrative privileges.

As this documentation is designed to be clear and helpful, please contact the system administrator if you encounter any issues or have suggestions for improvements.


## Developer Documentation
In-depth information for developers who want to contribute to the project or set it up for local development.

### System Architecture
An overview of the high-level architecture and interaction of system components.

### Repository Structure
Detailed description of the repository layout and where to find key elements.

### Technology Stack
Explanation of the technology choices including Python FastAPI, Next.js, Docker, and PostgreSQL.

## How to Run
Guidelines for running the system both in development and production environments.

### Local Development
Detailed steps for setting up and running the system on a local machine.

### Docker Deployment
Instructions for deploying the system using Docker containers.

## Contribution Guidelines
Guidance for those looking to contribute to the project including coding standards and how to submit pull requests.

## Testing
Information on the testing protocols and how to execute tests.

## FAQs
Quick answers to common queries regarding the use and development of the system.

## Additional Resources
Links to additional information such as demo videos and external support channels.

## Changelog
Documented log of all the changes made to the system over time.

## License
Information about the project's licensing and usage terms.

## Contact
Contact information for the project team for support or inquiries.

## Appendix
Any additional resources or information that supports the documentation.
