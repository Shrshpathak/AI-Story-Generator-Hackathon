# 📖 AI Story Generator with Image  

### 🚀 Project Objective  
The **AI Story Generator with Image** is an application that takes a **story idea (prompt)** from the user and automatically creates a **multi-part narrative with illustrations**.  
It blends **Natural Language Generation (NLG)** and **Text-to-Image Synthesis** to deliver an engaging, illustrated storytelling experience.  

This tool is designed for:  
- ✨ Creatives & Writers  
- 👩‍🏫 Educators  
- 🎮 Game Designers  
- 📚 Story Enthusiasts

## Instruction:
  - Use with GPU for faster generation
  - made using google collab

---

## ⚡ Functional Requirements & Core Features  

### 📝 User Input  
- Provide a **story idea** (short prompt or concept).  
- Choose additional settings:  
  - **Genre** (Fantasy, Sci-Fi, Mystery, Horror, Romance, etc.)  
  - **Tone** (Epic, Funny, Serious, Dark, Inspiring)  
  - **Target Audience** (Kids, Teens, Adults)  

### 📜 Narrative Generation  
- Expands the idea into a **multi-part narrative** (3–5 scenes).  
- Story follows structure:  
  - Introduction / Setting  
  - Conflict / Rising Action  
  - Climax  
  - Resolution  
- Text is coherent, stylistically consistent, and matches chosen **genre/tone**.  

### 🎨 Image Generation  
- For each **scene**, generate an **illustrative image** using a **Text-to-Image model**.  
- Image prompts are automatically extracted from scene text.  

### 📂 Output Format  
- Story is displayed **scene by scene**, each with:  
  - A **block of narrative text**  
  - A **corresponding AI-generated image**  

---

## 🛠️ Setup and Running  

### 🔧 Installation  

# Clone the repository
git clone https://github.com/your-username/AI-Story-Generator.git
cd AI-Story-Generator

# Install dependencies
pip install -r requirements.txt

▶️ Running the Application
streamlit run guvi.py

🌐 Live Demo

👉 https://ai-story-generator-hackathon-ng4u7nxdi8eq3qxauv5kby.streamlit.app/
