# Lab 2: Using Modules in Node.js

## Description

This lab demonstrates how to create and use custom modules in Node.js. It implements an event management system with various utility modules for validation, date formatting, and event status checking.

The lab showcases:
- Creating and importing custom modules
- Using built-in Node.js modules
- Environment variable management with dotenv
- Modular code organization

## Features

- **Event Validation**: Validates event data including title, date, and capacity
- **Date Formatting**: Formats dates in a human-readable format
- **Event Status**: Determines if an event is upcoming or past
- **Email Validation**: Validates email addresses using regex

## Project Structure

```
Lab2/
├── Lab2_UsingModules.js    # Main demonstration file
├── package.json            # Project dependencies and scripts
├── .env                    # Environment variables
├── config/
│   ├── constants.js        # Application constants
│   └── environment.js      # Environment configuration
└── utils/
    ├── helpers.js          # Helper functions (date formatting, status)
    └── validators.js       # Validation functions
```

## Prerequisites

- Node.js (version 14 or higher)
- npm

## Installation

1. Clone or download the project
2. Navigate to the Lab2 directory
3. Install dependencies:

```bash
npm install
```

## Usage

Run the lab demonstration:

```bash
npm run lab2
```

Or directly:

```bash
node Lab2_UsingModules.js
```

## Environment Configuration

The application uses environment variables defined in `.env`:

- `APP_NAME`: Application name
- `APP_PORT`: Port number

## Output

When you run the lab, you'll see tests for:
- Validating correct and incorrect event data
- Formatting dates
- Checking event status (past/upcoming)
- Validating email addresses

## Learning Objectives

After completing this lab, you should understand:
- How to create and export modules in Node.js
- How to import and use custom modules
- Modular code organization principles
- Environment variable management
- Basic validation and utility functions