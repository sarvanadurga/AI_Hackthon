# AI_Hackthon
For TDD design form the recording transcript suing  Azure AI foundry directly link  with Jira back log
**Overview**

This project demonstrates generating a Technical Design Document (TDD) directly from meeting recordings or transcript text using Azure AI Foundry. It also integrates with Jira to break down the TDD into backlog tasks, enabling a streamlined workflow from meeting notes to actionable items.

**Features**

Automatic TDD generation: Converts meeting transcripts into a structured TDD.

Backlog task creation: Extracts tasks from the TDD and formats them for Jira.

Azure AI Foundry integration: Uses GPT-4o for AI-assisted content generation.

Direct link support: Meeting recordings can be supplied as text or SharePoint URLs.

**Workflow**

Prepare transcript: Convert meeting recordings to clean text format.

Load into Chat Playground: Paste transcript in Azure AI Foundry Playground.

Generate TDD: Use GPT-4o to produce a structured Technical Design Document.

Extract backlog tasks: Identify actionable items from the TDD.

Jira integration: Push backlog tasks to the relevant Jira project (optional for demo).

**Usage**

Open the Azure AI Foundry Chat Playground.

Paste your meeting transcript.

Ensure the system prompt is set to generate a structured TDD.

Click Generate to view the TDD and backlog tasks.

(Optional) Copy the backlog tasks to Jira using your project URL.
