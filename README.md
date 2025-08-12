# Auto-Ticket-Classifier-And-Responder
Automate the processing, classification, and response generation for customer support tickets using AI (LLM).

```
Incoming Ticket (API/Webhook)
       │
       ▼
Preprocessing (clean text, extract metadata)
       │
       ▼
Classification (LLM/ML Model)
   - Urgency (High, Medium, Low)
   - Intent (Refund, Complaint, Tech Support, Inquiry, Other)
       │
       ▼
Response Generation (LLM prompt based on classification)
       │
       ▼
Store in Database (PostgreSQL)
       │
       ▼
Notification (Slack/Email/Webhook)

```


