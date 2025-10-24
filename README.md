# Woohoo! My Automated AI Email Agent: n8n + Google Gemini

### My Little Low-Code Helper for Sending Smarter Emails with AI!

Hey there! This project is basically my go-to workflow for automating email replies. It uses n8n to run things and Google Gemini (or whatever AI model you like) to write smart, personalized emails.

The big idea here? Taking slow, manual tasks and building an AI agent that handles them for me. It shows how you can mix simple automation tools with powerful AI to save a ton of time.

## What It Can Do

-**Agent Mode:** It's smart! The core AI Agent decides if it needs to use a tool—in this case, sending an email via the Gmail connection.

-**Smart Replies:** Thanks to the Google Gemini Chat Model, it understands the incoming message and writes a great, contextual reply.

-**Remembers Stuff:** It uses a Simple Memory Buffer so it doesn't forget what you talked about if you have a follow-up conversation.

-**Drafts Emails for You:** The Gmail Tool takes the AI's perfect subject and body and drafts the email automatically. So easy!

-**Super Flexible:** You can tweak this template for anything: customer service, internal messages, or even just routing simple questions.

## Tech Used (Just the important bits!)

This workflow runs on a few key components:

-**Automation Brain (n8n):** This is what runs the whole show, managing triggers and connecting everything.

-**The Intelligence (Google Gemini Chat Model):** This is the smart part—it reads the message, reasons, and writes the response.

-**The Action (Send a message in Gmail):** This is the 'hand' the AI uses to actually send or draft the email.

-**The Memory (Simple Memory):** Keeps the chat history fresh so replies make sense.

-**The Start Button (Chat Trigger):** This is what kicks off the whole workflow when a new message comes in.

## Wanna Run It? Here's How!

**1)Get the File:** Copy the content of the email_agent.json file. Then, in your n8n workspace, just paste the JSON to import the workflow.

**2)Connect Your Accounts:**

-**Gemini:** You'll need to set up your Google Gemini API credentials in n8n and link them to the Google Gemini Chat Model.

-**Gmail:** You'll also need to link your Gmail account using OAuth2 for the email-sending node.

**3)Go Live:** Activate the workflow! Grab the webhook URL from the trigger node and send a test message to see the magic happen.

## Quick Ideas for Using This

-**Triage Support:** Let the AI draft answers for your easiest and most common questions.

-**Lead Starter:** It can send quick info to new leads based on what they asked for.

-**Team Routing:** Have the AI summarize incoming messages and draft a quick forwarding note to the right person.

Enjoy the automation!
