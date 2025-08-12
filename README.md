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



## 🏢 Real Estate Ticket Example

### 📩 Incoming Ticket
Subject: Noise Complaint from Upstairs Unit
Body: I live in Unit 204 and the tenants in Unit 304 have been making loud noises past midnight almost every day. I’ve spoken to them once but the problem continues. Please take action soon as it is affecting my sleep and work.

### 🧠 AI Classification
```json
{
  "urgency": "High",
  "intent": "Complaint"
}


AI-Generated Response
Dear [Tenant Name],

Thank you for bringing this matter to our attention. We understand how disruptive excessive noise can be to your comfort and well-being. We will address this matter with the occupants of Unit 304 immediately and remind them of the community quiet hours.

If the noise persists, please document the dates and times so we can take further action.

We appreciate your patience and cooperation.

Sincerely,  
[Property Manager Name]  
Leasing Office


