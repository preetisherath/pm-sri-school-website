# PM SHRI School Chatbot

A simple AI-powered chatbot designed to answer questions about PM SHRI Government Senior Secondary School, Mandal, Bhilwara using information extracted from the school's website.

## Features

- Answers questions about admissions, academics, facilities, timings, contact information, vision, achievements, and values
- Natural language processing through keyword matching
- Responsive design for mobile and desktop
- Interactive suggestion chips for common queries
- Typing simulation for better user experience

## Files Included

1. `chatbot.html` - Main chatbot interface with embedded JavaScript
2. `school_knowledge_base.txt` - Extracted information from the school website

## How to Use

### Option 1: Open in Browser (Recommended)
1. Simply open `chatbot.html` in any web browser (Chrome, Firefox, Safari, Edge)
2. Start asking questions about the school in the chat interface
3. Use the suggestion chips for common questions or type your own

### Option 2: Integrate into Existing Website
1. Copy the JavaScript code from `chatbot.html` (between `<script>` tags)
2. Paste it into your existing website where you want the chatbot to appear
3. Ensure you have the knowledge base data available in your JavaScript

## Sample Questions You Can Ask

- "What are the admission procedures?"
- "What streams are offered at the senior secondary level?"
- "What facilities does the school have?"
- "What are the school timings?"
- "How can I contact the school?"
- "What is the school's vision and mission?"
- "What achievements has the school earned?"
- "What are the school's core values?"

## Technical Details

The chatbot works by:
1. Maintaining a knowledge base of school information extracted from the website
2. Using keyword matching to identify the topic of user questions
3. Providing relevant responses from the appropriate knowledge base category
4. Falling back to general helpful responses when no specific match is found

## Customization

To update the chatbot with new information:
1. Edit the `knowledgeBase` object in the JavaScript section of `chatbot.html`
2. Add new categories or update existing ones with relevant keywords and responses
3. Each category should have:
   - `keywords`: Array of words that trigger this category
   - `responses`: Array of possible responses (one is selected randomly)

## Requirements

- Modern web browser with JavaScript enabled
- No server-side code required (pure client-side solution)
- No external dependencies or APIs needed

## Notes

- This is a session-based chatbot that runs entirely in the browser
- All knowledge base data is stored locally in the JavaScript code
- For production use with larger knowledge bases, consider integrating with a backend service
- The current implementation is designed for educational/demo purposes