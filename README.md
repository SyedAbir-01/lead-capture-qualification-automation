# Lead Capture & Qualification Automation

An n8n workflow that captures incoming business leads, validates their information, scores their intent, and routes them into different follow-up paths.

## Workflow

```text
Lead submits form
        ↓
On Form Submission
        ↓
Edit Fields
        ↓
Validate Lead
        ↓
Score Lead
        ↓
Route by Priority
   ┌────┼────┐
 HIGH MEDIUM LOW
   ↓     ↓     ↓
Action Action Action
