# AI Sales Intelligence Assistant - Setup Guide

This guide explains how to set up and configure the AI Sales Intelligence Assistant developed by AI Weekline.

## Prerequisites

- Google Gemini API access
- Make.com account
- Gmail account
- Google Sheets account
- Basic knowledge of Git and GitHub

## Installation Steps

### Step 1: Clone the Repository

This project can be cloned from GitHub using the following command:

```bash
git clone https://github.com/shashanksingh-ai/ai-sales-intelligence-assistant.git
```

Move into the project directory:

```bash
cd ai-sales-intelligence-assistant
```

### Step 2: Configure Google Gemini API

1. Create a Google AI Studio account.
2. Generate a Gemini API Key.
3. Store the API key securely.
4. Add the API key to your Make.com scenario.

### Step 3: Configure Gmail

- Connect your Gmail account to Make.com.
- Grant the required permissions.
- Configure Gmail as the workflow trigger.

### Step 4: Configure Google Sheets

- Create a Google Sheet for storing customer data.
- Connect Google Sheets to Make.com.
- Map all required fields.

### Step 5: Build the Make.com Scenario

The Make.com workflow should follow this sequence:

Gmail
↓
Google Gemini
↓
Google Sheets
↓
AI Email Reply

### Step 6: Test the Workflow

Send a sample customer email and verify:

- Gmail trigger executes successfully.
- Google Gemini analyzes the email.
- Customer information is stored in Google Sheets.
- AI-generated reply is created.
- No workflow errors occur.

### Expected Output

After successful setup, the assistant will automatically:

- Detect incoming customer emails.
- Analyze email content using Google Gemini.
- Extract structured business insights.
- Store data in Google Sheets.
- Generate AI-powered customer responses.

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Gmail not triggering | Reconnect Gmail permissions |
| Gemini API error | Verify API key |
| Google Sheets not updating | Check Sheet permissions |
| Make.com scenario fails | Review module configuration |

## Conclusion

The AI Sales Intelligence Assistant is now configured and ready for production use.
