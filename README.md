# 📚 AI Storybook Generator

![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow)
![Automation](https://img.shields.io/badge/Automation-n8n-orange)
![AI](https://img.shields.io/badge/AI-LLM%20%2B%20Image%20Generation-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

An **AI-powered Kids' Storybook Generator** that automatically creates illustrated storybooks through a chatbot conversation.
The system collects user input via a chatbot, generates a story with images using AI models, compiles everything into a **PDF book**, and delivers it to the user via a **shareable Google Drive link**.

---

## 🎬 Project Demo

Watch the full demo of the AI Storybook Generator:

[![AI Storybook Generator Demo](https://img.youtube.com/vi/U5-7mfDizsk/0.jpg)](https://youtu.be/U5-7mfDizsk)

---

# 📖 Project Overview

The **AI Storybook Generator** is designed to automatically create visually appealing children's storybooks.

Instead of manually writing stories and generating images page by page, users simply interact with a chatbot. The system collects the required information and automatically generates:

* A story
* AI-generated illustrations
* A complete storybook
* A compiled PDF

The final book is uploaded to **Google Drive** and shared with the user through a link.

---

# ❗ Problem Statement

## Role of Storybooks

Storybooks play a crucial role in early childhood development. They help children understand:

* Moral values
* Right vs wrong
* Imagination and creativity

## Need

Currently, generating a fully illustrated storybook requires:

* Writing the story manually
* Generating images individually
* Compiling pages manually into a PDF

Existing AI chatbots can generate stories and images, but:

* The workflow is not automated
* Image prompts must be written manually
* Only a limited number of images can be generated
* The final book must be compiled manually

This creates a **time-consuming and complex process**.

---

# 💡 Proposed Solution

We developed an **AI-based automated storybook generation system** with a chatbot interface.

### The system:

1. Collects story details through a chatbot conversation
2. Generates a story using an LLM
3. Creates illustrations using an AI image model
4. Combines story text and images into slides
5. Compiles the slides into a **PDF book**
6. Uploads the book to **Google Drive**
7. Sends the **download link to the user**

---

# 🧰 Tools and Technologies

| Category             | Technology           |
| -------------------- | -------------------- |
| Programming Language | JavaScript           |
| LLM                  | gpt-oss-120b         |
| AI Provider          | Groq                 |
| Image Generation     | Z-Image-Turbo (Fast) |
| Automation           | n8n                  |
| Hosting              | Modal                |
| Chatbot Interface    | AI Agent Node (n8n)  |
| Storage              | Google Drive         |

---

# ⚙️ System Workflow

### Step-by-Step Process

1. User interacts with the AI chatbot.
2. Chatbot gathers required story information.
3. Input is sent to a **format checker**.
4. Data is routed to the appropriate automation nodes.
5. A new **book folder** is created in Google Drive.
6. A **slide presentation** is generated from a template.
7. AI generates:

   * Story protagonist
   * Poem/story text
8. A prompt for the **book cover image** is created.
9. The prompt is sent to the **image generation model**.
10. Image is generated in **Base64 format**.
11. Converted into **PNG binary file**.
12. Uploaded to Google Drive.
13. Permissions are updated to allow sharing.
14. The same process repeats for all **storybook pages**.
15. Images are sorted and inserted into slides.
16. Slides are compiled into a **PDF book**.
17. PDF is uploaded to the book folder.
18. Share permissions are enabled.
19. The **Google Drive link** is sent to the user.

---

# 🏗 System Architecture

The system consists of four main layers:

1️⃣ **User Interaction Layer**

* Chatbot interface using n8n AI Agent

2️⃣ **Processing Layer**

* LLM generates story content
* Prompt engineering for images

3️⃣ **Image Generation Layer**

* Z-Image-Turbo model generates illustrations

4️⃣ **Storage & Output Layer**

* Google Drive stores images and PDF
* Final PDF shared with user

---

# 🧪 Testing

The system was tested in three major areas:

### Chatbot

* Conversation flow
* Input validation
* Response accuracy

### Generation System

* Story generation quality
* Image generation reliability

### Storage System

* Google Drive folder creation
* File uploads
* Permission handling

All workflow nodes were tested individually before integration.

---

# ⭐ Key Features

* ⚡ Fast response time
* 🤖 AI-powered automation
* 💬 User-friendly chatbot interface
* 🧠 Intelligent conversation handling
* 🖼 AI-generated story illustrations
* 📚 Automatic storybook compilation
* 📄 PDF generation
* ☁️ Cloud storage via Google Drive
* 🔗 Instant download link for users

---


# ⚠️ Challenges Faced

* Handling diverse user queries
* Managing AI-generated outputs
* Integration of multiple AI tools
* Prompt engineering for agents
* Finding **free image generation models**
* Hosting models with limited resources
* Maintaining **text-on-image quality**
* Google Drive file management
* File format conversion
* Error handling and workflow reliability

---

# 🎯 Learning Outcomes

Through this project we gained practical experience in:

* AI system design
* Automation with **n8n**
* Chatbot development
* Working with **Large Language Models**
* Image generation models
* API integration
* Cloud and self-hosted AI deployment
* File and storage management
* Team collaboration and project management

---

# 📊 Expected vs Achieved Outcomes

The expected outcome was:

> Generate a fully illustrated storybook and deliver it as a downloadable PDF.

✅ **Outcome Achieved Successfully**

Example generated book:

https://drive.google.com/file/d/154WMalnlxfr2GuRPhWQUABL1P7rW3BiV/view?usp=drive_open

---

# 📌 Conclusion

The **AI Storybook Generator** demonstrates how modern AI tools can automate complex creative workflows.

By integrating **chatbots, LLMs, image generation models, and automation tools**, the system allows users to generate a complete illustrated children's storybook with minimal effort.

This project highlights the potential of **AI-powered creative automation** in education and entertainment.

---

## 🙏 Acknowledgments / Inspiration

This AI Storybook Generator was inspired by **Nadezhda Privalikhina**.  

Learn more about her work:  
- 🔗 LinkedIn: [Nadezhda Privalikhina](https://www.linkedin.com/in/nadezhda-privalikhina/)

🎥 Inspired Project Demo:  
[![Watch Nadezhda’s Demo](https://img.youtube.com/vi/RgR-VcNh9Uk/0.jpg)](https://www.youtube.com/watch?v=RgR-VcNh9Uk)

---

## 📫 Contact / Connect

For more information about the project or to connect professionally:  
- LinkedIn: [Tayyab Ghafoor](https://www.linkedin.com/in/tayyab-ghafoor-6044a6269/)

---

# 📄 License

This project is created for **academic purposes**.
