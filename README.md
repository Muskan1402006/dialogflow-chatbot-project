# Dialogflow Chatbot Project

This project is created by following a YouTube tutorial to build a chatbot using Dialogflow.

---

## Day 2 Progress — Intents and Entities

Today I learned how Dialogflow works with Intents and Entities.

### What I implemented

- Created basic greeting intent
- Created fallback intent
- Created custom intents for user queries
- Learned how entities extract important words from user sentences
- Created custom entities for chatbot understanding

### Screenshots

All screenshots are available in: `screenshots`

### Key Learning

Intents decide *what user wants* and Entities decide *what information to extract* from user sentence.

## Day 3 Progress — Dialogflow Messenger Integration into Website

Today I connected my Dialogflow agent to a real HTML webpage using Dialogflow Messenger and tested it successfully in the browser.

### What I implemented

- Embedded Dialogflow Messenger script in an HTML page
- Connected the chatbot using my Agent ID
- Set the welcome intent (WELCOME)
- Customized the chat title to "FirstBot"
- Tested successfully on localhost using Live Server

---

## Day 4 Progress — Knowledge Base Integration

Today I learned how to use the Knowledge Base feature in Dialogflow to make the chatbot answer questions automatically from documents and web content.

### What I implemented

- Created a Knowledge Base inside Dialogflow
- Added a document / FAQ content as knowledge source
- Enabled Knowledge Base responses for user questions
- Tested automatic answers generated from the document
- Understood how Dialogflow uses machine learning to fetch answers from data instead of fixed intents

### What I learned

Knowledge Base allows the chatbot to answer questions from large content like:
- FAQs
- Documents
- Website pages

This reduces the need to create many manual intents.

### Screenshots

All screenshots are available in:

screenshots/day-4

### Key Learning

I learned how to make the chatbot intelligent by connecting it to a Knowledge Base so it can answer dynamic questions from provided content.

---

## Day 5 Progress — Knowledge Space (Advanced Knowledge Base)

Today I explored deeper into Dialogflow Knowledge Base and understood how Knowledge Space helps the chatbot answer more accurate and contextual questions from large data sources.

### What I implemented

- Improved the existing Knowledge Base
- Added more questions and content to increase answer accuracy
- Tested multiple user questions based on the same document
- Observed how Dialogflow picks the most relevant answer from the knowledge source
- Understood difference between Intents response and Knowledge Base response

### What I learned

Knowledge Space allows the chatbot to:
- Handle large FAQs without creating many intents
- Provide dynamic answers from documents and web pages
- Improve user experience with better automated responses

### Screenshots

All screenshots are available in:

screenshots/day-5

### Key Learning

I learned how to enhance chatbot intelligence using Knowledge Space so it can answer a wide variety of user queries from uploaded knowledge sources without manual intent creation.
---

## Day 6 — Completed Video 1

- Revised full chatbot flow in Dialogflow
- Tested intents, entities, and knowledge base together
- Verified chatbot working in `public/index.html`
- Confirmed end-to-end response from user message to bot reply

**Learning:** Understood complete process of building and running a Dialogflow chatbot on a webpage.