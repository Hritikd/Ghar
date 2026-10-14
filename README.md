# Ghar

**An interactive prototype of an AI family assistant for working parents in India, turning school and household messages into shared tasks and reminders.**

## Try it in 30 seconds

Open `index.html` in a browser. No install, account or API key is needed.

1. Choose a school circular, electricity bill or apartment message.
2. Click **Make a plan** to see a prepared summary, deadline and source excerpt.
3. Switch the summary between English, Hindi and Kannada.
4. Assign the task to a family member and add it to the demo plan.
5. Complete a task or download an `.ics` calendar reminder.

## Consumer thesis

**Initial user:** working parents with school-age children, where one person carries most of the household's remembering and coordination.

**Starting problem:** useful obligations are buried in school and apartment group messages. Reading a summary is not enough: someone must own the task and follow through.

**First use case:** turn a school circular into a reviewed task, named owner and reminder. Bills and apartment notices are adjacent use cases demonstrated here.

**Why AI:** a production system would interpret variable message formats and mixed-language inputs, extract dates and obligations, retain source evidence, and ask when information is ambiguous. Deterministic rules should handle scheduling and permissions after review.

**Distribution hypothesis:** start with parent communities. Sharing responsibility with a partner creates a natural invitation moment. This is a hypothesis, not a proven growth loop.

**Retention hypothesis:** repeat household obligations bring families back. Measure households returning in week four, tasks completed on time, and households with two active members. Opening the app alone is not sufficient evidence of value.

**Revenue hypothesis:** test a household subscription around ₹99/month after users experience repeat value. Validate willingness to pay and inference/support costs before treating this as a business model.

**What could invalidate the idea:** forwarding messages may be too much effort; partners may not participate; existing calendars may be sufficient; extraction errors may destroy trust. Test these before adding more features.

## What works today

- Three curated, fictional scenarios
- Prepared summaries in three languages
- Task assignment labels, completion and duplicate prevention
- Downloadable calendar event files
- Responsive, dependency-free HTML/CSS/JavaScript

## What is simulated

This is a product interaction prototype, not a production AI application. Summaries and extracted fields are predefined. There is no model call, OCR, upload processing, WhatsApp connection, payment, live notification or cross-device sharing. Tasks exist only in memory and reset on reload. Selecting a family member does not contact or invite anyone. Calendar downloads must be opened and imported by the user. Sample dates are fixed in October 2026.

## Validation

JavaScript syntax and the three sample flows, summary language switching, task creation and duplicate prevention were checked in a Node DOM stub. This does not replace real-browser, mobile, accessibility or calendar-client testing.

## Before a real pilot

Recruit a small group of working-parent households. Validate the task-sharing behavior first. Add opt-in message intake, a structured extraction pipeline, uncertainty handling, persistent household permissions, editable tasks, deletion controls and reliable reminders. Evaluate date, amount and obligation extraction against annotated examples, including ambiguous and mixed-language messages. Minimize storage of children's and household information.

Built by Hritik Datta as a consumer AI product concept.
