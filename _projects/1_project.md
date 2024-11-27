---
layout: page
title: project 1
description: with background image
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

## Welcome to the Tools Section

Explore our innovative tools! Below is a prototype for **Project 1**, where you can upload your floor plan and get personalized insights.

### Upload Your Floor Plan
<form id="floor-plan-upload" method="POST" enctype="multipart/form-data" action="/upload">
  <label for="file-upload">Select your floor plan (PDF or Image):</label><br>
  <input type="file" id="file-upload" name="floor_plan" accept=".pdf, .png, .jpg, .jpeg" required><br><br>
  <button type="submit">Upload</button>
</form>

### Chat with AI
Use our integrated ChatGPT-powered assistant to get insights about your house:

<div id="chat-container">
  <iframe
    src="https://chat.openai.com/chat"
    title="Chat with AI"
    style="width: 100%; height: 500px; border: none;"
  ></iframe>
</div>
