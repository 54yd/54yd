# 🩷 I love to people make happy by Computer Science. 🩷 

#### *FYI: THE PROFILE ICON IS DRAWN BY MYSELF~! 🎨✨️

## My Personal Statement 👋
---
Growing up in Japan, I encountered heavy bullying when I was 13. An experience that left me grappling with its traumatic impact. This incident opened my eyes to the stark reality of Human Activity(Brain, Mental, Spirit) and inspired me to advocate for change in our legal and social security systems. Also, I believe that these 30 years of BAD ECONOMY in Japan changed All Japanese Minds because I was raised in a poor environment. I am pursuing the truth, the Economy, and Financial relation to Human Activity by using Technology and Computer Science.

Driven by these challenges, I've developed a passion for exploring how technology can play a role in preventing crime and supporting victims:

1. **Preemptive surveillance**: Implementing AI-powered systems to monitor potential criminal activities and intervene before harm occurs.  
2. **Therapeutic interventions**: Using AI to identify at-risk individuals and offer targeted therapy. (offering Game App for complementing violent action in real life etc.)  
3. **AI-driven support for victims**: Empowering crime survivors, especially children, with AI assistants that facilitate access to appropriate treatment and support networks.

My ultimate goal is to pioneer the development of an unbiased, automated investigation system that collects and preserves evidence, complementing traditional policing methods. I love seeing people smile and want to create a society where everyone can live safely and happily.

In pursuing my master's degree in Engineering at your esteemed institution, I aim not only to expand my technical knowledge but also to collaborate with like-minded individuals dedicated to making a tangible difference in society through technology.


# 🌟 Portfolio Projects 🌟

Welcome to my portfolio repository! Below are four of my recent projects that showcase my skills in web development, augmented reality, e-commerce platforms, and AI-driven applications. 🎉 Each project demonstrates my ability to design, build, and deploy engaging applications. 🚀

---

## 🎬 [Project 1: Movie Auto Cutter - "Graham" ✂️](https://github.com/54yd/graham)

**Description**: Movie Auto Cutter is a tool for segmenting videos based on timestamps or subtitle files, perfect for language learning, AI data preparation, and educational content editing. Simply upload a video and provide timestamps or an SRT file to auto-generate segmented clips. 🎥

**Technologies**: NextJS15, Vercel deployment-ready 🌐

**Features**:
- 📂 **Local and Cloud Deployment**: Easily deploy on Vercel with `npm run start`.  
- 🤖 **AI and Education-Friendly**: Generate specific video clips for AI training or language practice.  
- 🎓 **Use Cases**: Language learning, dataset generation, and video summarization.

---

## 🐾 [Project 2: AR Animal Interaction Website - "Kimaris" 🦁](https://github.com/54yd/kimaris)

**Deployed Web Site**: https://kimaris.vercel.app

**Description**: A mobile-optimized augmented reality platform for interacting with 3D animals. Users can place animals in AR, engage in mini-games, and enjoy real-time audio feedback that changes based on interactions. 📱

**Technologies**: React, ARKit, ServiceWorker(OfflineTechnology), PWA(installable), Web Audio API 📳

**Features**:
- 🌍 **AR 3D Animal Placement**: Place virtual animals on real surfaces.  
- 🛍️ **Offline Function**: This app can use as music player when Offline! (first access needed)  
- 🧡 **HP-Based Interactions**: Engage in interactive games with animals.  
- 🔊 **Real-Time Audio Manipulation**: Dynamic audio that adjusts pitch and speed based on gameplay.

---

## 🛍️ [Project 3: E-Commerce Framework - "Palette" 💳](https://github.com/54yd/palette)

**Description**: A modern e-commerce web application framework featuring user authentication, product management, and a component-based UI design. 🛒

**Technologies**: TypeScript, React, Next.js, Jest, Prisma 🖥️

**Features**:
- 🔐 **User Authentication**: Support for Google, Apple, and GitHub login.  
- 🧪 **Jest Testing**: Integrated QA tests with Jest.  
- 👥 **Product Management**: Full CRUD operations for product listings.  
- 📊 **EC Schema**: Ready-to-deploy database schema.  
- 🧩 **Reusable Components**: Includes sample components for authentication, product display, and user management.

---

## 🕵️‍♂️ [Project 4: Shiki – AutoCrimeDetector 🔍](https://github.com/54yd/shiki)

**Description**: An automated crime-detection application that analyzes CCTV screenshots (or any image), pinpoints suspects or objects of interest, and returns their normalized `[x, y]` coordinates. 🛰️

**Technologies**: Python, Gradio, Transformers (`showlab/ShowUI-2B`, `Qwen/Qwen2-VL-2B-Instruct`) 🤖

**Features**:
- 🤖 **AI-Powered Detection**: Uses ShowUI + Qwen2-VL to understand and localize elements in images.  
- 🎯 **Coordinate Extraction**: Returns precise relative coordinates for detected targets.  
- 🌐 **Gradio Interface**: Quick web UI for uploading images and querying detection.  
- ⚙️ **Easy Setup**: Auto-downloads required model weights from Hugging Face Hub.


---

## 🚨 Collaboration: Graham → Shiki for Crime Prevention 🚨

To create a robust, end-to-end crime analysis pipeline, **Graham** and **Shiki** work in tandem:

1. **Video Segmentation (Graham)**
   - Graham processes raw CCTV footage and segments it into timestamped screenshots using subtitle or timestamp inputs.
2. **Automated Detection (Shiki)**
   - Each screenshot is fed into Shiki’s AI-powered detection API to identify and retrieve coordinates of persons or objects of interest.
3. **Integrated Workflow(FYI: STILL DEVELOPMENT...SO YOU CAN USE THIS PARTIALLY, this is still experiment)**
   ```bash
   # Segment video into frames
   python -m graham.segment --video scene.mp4 --srt subtitles.srt --output frames/

   # Run Shiki on each frame
   for img in frames/*.png; do
     python client/showui_gradio.py --image "$img" --prompt "Find suspect"
   done
   ```
4. **Research Impact**
   - This combined pipeline enables researchers to automatically convert hours of footage into structured data, facilitating rapid analysis, pattern discovery, and evidence preservation.

By connecting these two open-source tools, we move closer to a proactive crime-prevention ecosystem driven by AI and data.

---
