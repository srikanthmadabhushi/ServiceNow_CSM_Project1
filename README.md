# ServiceNow_CSM_Project1
CSM Project 1: GenAI Sentiment &amp; Auto-Response Flow
# ServiceNow CSM | GenAI Sentiment & Empathy Auto-Response Flow (Yokohama PDI)

## Overview
This project integrates simulated **Generative AI** logic into ServiceNow CSM workflows.  
It analyzes customer case descriptions to detect emotional tone (Positive, Negative, Neutral), assigns sentiment, and auto-generates an empathetic AI response.

## Flow Summary
1. **Trigger:** When a Customer Case is created or updated.
2. **AI Logic:**
   - Detect keywords expressing tone.
   - Assign corresponding sentiment.
   - Generate AI Suggested Response and Notes.
3. **Update Record:** The flow updates Sentiment, AI Suggested Response, and AI Notes automatically.

## Highlights
- Built on **Yokohama PDI**
- No-code **Flow Designer** automation
- Demonstrates **AI reasoning** and customer empathy simulation
- Fully customizable for real AI integration (OpenAI, Now Assist)

## Flow Diagram
![Flow Diagram](Diagrams/Flow Diagram.png)

## Example Outputs
| Short Description | Sentiment | AI Response |
|--------------------|------------|--------------|
| “Portal not working!” | Negative | Apology message |
| “Thanks for fixing it!” | Positive | Appreciation message |
| “Need help with login” | Neutral | Acknowledgment message |

## Business Impact
- Reduces response time  
- Improves customer satisfaction  
- Demonstrates **AI-driven automation** potential within ServiceNow CSM
