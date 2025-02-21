## King Obafemi Abejirin Linux Summative Execution Instructions

# Submission Reminder Application

Welcome to the Submission Reminder Application! This tool helps students stay on top of their assignments and ensures they submit them on time. Below, you'll find detailed instructions on how to set up and use the application.

## Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [How It Works](#how-it-works)

## Prerequisites

Before you begin, ensure you have the following installed:

- **Bash**: This application is built using Bash scripts, so you will need a Unix-like environment (Linux or macOS). If you're on Windows, consider using WSL (Windows Subsystem for Linux).
- **Tree Command**: This tool will help you visualize the directory structure. You can install it using your package manager:
  - For Ubuntu/Debian: `sudo apt install tree`
  - For macOS: `brew install tree`

## Installation

1. **Clone the Repository**: If you haven't already, clone the repository to your local machine.

git clone <repository-url>
cd <repository-name>

2. **Run the Setup Script**: Execute the setup script to create the necessary directories and files.
chmod +x create_environment.sh
./create_environment.sh

3. **Provide Your Name**: When prompted, enter your name. This will create a personalized submission reminder directory.


## Running the Application

1. **Navigate to Your Directory**: Change into your submission reminder directory.

cd submission_reminder_<your_name>

2. **Execute the Startup Script**: Run the startup script to initiate the reminder process.
./startup.sh

3. **View Output**: The application will display information about your assignments and remind you of any submissions that are due.

## How It Works

The application retrieves data from a submissions file, which includes information about students and their assignment statuses. It monitors for any assignments that haven't been submitted and sends reminders as needed.

---

Thank you for using the Submission Reminder Application
