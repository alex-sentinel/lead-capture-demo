# Lead Capture Demo

A lead-capture system for small businesses. When someone fills out a
contact form, their info is automatically saved and organized. No manual
copying, no lost leads.

## What it does

- A visitor submits a contact form (name, email, message)
- The submission is sent to an [n8n](https://n8n.io) automation workflow
- The workflow logs each lead as a new row in a Google Sheet

The result: each lead lands in one place automatically, the moment
it comes in.

## How it works

- **Front end:** HTML contact form
- **Automation:** n8n workflow triggered by a webhook
- **Storage:** Google Sheets, appended one row per submission

Form → Webhook → Google Sheets

## About this project

I'm an 18 year old learning web development and automation. This is an early,
in-progress build. It is the first version of a lead-capture system I'm developing
for real small businesses.

I designed the workflow, wired the automation, connected the data flow, and
debugged the integration end to end. The front end form is intentionally
simple; the focus of this project is the working automation behind it.

## What's next

- Auto reply email to the person who submits
- Instant notification to the business owner when a lead comes in
- A cleaner, well designed form

More to come as I keep building.