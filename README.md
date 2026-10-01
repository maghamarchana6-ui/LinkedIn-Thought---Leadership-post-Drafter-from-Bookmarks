<img width="1736" height="325" alt="image" src="https://github.com/user-attachments/assets/955ab721-1762-4487-9a59-937109a2a37a" />
# LinkedIn Thought-Leadership Post Drafter from Bookmarks

An AI-powered n8n automation workflow that converts useful articles into professional LinkedIn thought-leadership posts.

## 🚀 Project Overview

This project automates the process of reading an article, extracting its important insights, and transforming them into an engaging LinkedIn post.

Currently, the workflow accepts an article URL through a form. It fetches the webpage content, analyzes the article using AI, generates a LinkedIn post, and stores the final post in Google Sheets.

## 🔄 Workflow

Form Submission
↓
HTTP Request
↓
HTML Content Extraction
↓
AI Article Analysis
↓
AI LinkedIn Post Generation
↓
Edit Fields
↓
Google Sheets

## ⚙️ How It Works

1. **Article URL Input**
   - The user submits an article URL through a form.

2. **Article Fetching**
   - The HTTP Request node retrieves the webpage content.

3. **Content Extraction**
   - The HTML node extracts the relevant article content.

4. **AI Analysis**
   - The first AI model identifies:
     - Main topic
     - Important facts and statistics
     - Counter-intuitive insights
     - Professional takeaways
     - LinkedIn-relevant context

5. **LinkedIn Post Generation**
   - A second AI model transforms the analysis into a professional LinkedIn post with:
     - Strong hook
     - Key insights
     - Statistics
     - Professional takeaways
     - Discussion question
     - Relevant hashtags

6. **Output Processing**
   - The generated post is stored in the `Linkedin_post` field.

7. **Google Sheets Storage**
   - The final LinkedIn post is automatically added to a dedicated `LinkedIn Posts` sheet.

## 🛠️ Technologies Used

- n8n
- AI / Large Language Models
- HTTP Request
- HTML Content Extraction
- Google Sheets
- Form Trigger

## 🎯 Project Goals

- Reduce the time required to create LinkedIn content
- Extract valuable insights from long-form articles
- Convert research into professional social media content
- Automate repetitive content creation tasks
- Maintain fact-based and engaging LinkedIn posts

## 🔮 Future Improvements

- Integrate Pocket or Raindrop for automatic bookmark retrieval
- Automatically process multiple saved articles
- Add scheduled workflow execution
- Avoid processing the same article multiple times
- Add different LinkedIn writing styles
- Track generated posts and article sources

## 👨‍💻 Project Status

**Current Status:** Working Prototype

The current version accepts article URLs through a form and automatically generates and stores LinkedIn thought-leadership posts.

Future versions will integrate bookmark services such as Pocket or Raindrop for fully automated article processing.
