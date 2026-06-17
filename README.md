# Travel Leads Automation

An AI-assisted workflow for travel agents that intakes client trip information, processes it through an AI assistant, and logs structured lead details into a spreadsheet for follow-up.

## Overview

This project was built in Pipedream as an automation workflow for travel lead intake. The workflow accepted incoming client trip information, used an AI chat step to interpret and structure the request, applied custom JavaScript/Node.js logic, and then added the final lead information to a spreadsheet.

## Workflow

1. Webhook receives client travel inquiry
2. AI chat step extracts and organizes key trip details
3. JavaScript/Node.js step cleans and formats the output
4. Spreadsheet step logs the structured lead for follow-up

## Tools Used

- Pipedream
- Webhooks
- JavaScript / Node.js
- AI chat step
- Spreadsheet integration

## What It Solved

Travel agents often receive unstructured client requests with details like destination, dates, budget, number of travelers, and preferences spread across messages. This workflow helped turn that information into organized lead records that could be tracked and followed up on more easily.

## Status

This project is no longer actively maintained, but it demonstrates my experience designing AI-assisted automation workflows using webhooks, LLMs, JavaScript, and third-party integrations.

## What I Learned

- How to design an automation workflow from intake to output
- How to use AI to structure unorganized user information
- How to connect AI outputs to downstream tools
- How to use JavaScript to clean and transform workflow data
- Why long-term maintenance, testing, and monitoring matter for automations
