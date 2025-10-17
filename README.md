👋 Hi, I'm Md Ahad Ali
🎓 2nd Year Undergraduate | Institute of Information Technology (IIT), Jahangirnagar University
🤖 Passionate about Machine Learning, Research, and Real-time Python Projects

<!-- Animated Banner --> <p align="center"> <img src="https://raw.githubusercontent.com/mdahadali/mdahadali/main/assets/ahad-animated-banner.gif" alt="Md Ahad Ali Banner" width="600"/> </p>
🧠 About Me
I am a dedicated computer science student focused on exploring Machine Learning concepts and real-world applications through research and hands-on projects.
I enjoy developing Python-based projects that solve practical problems and strengthen my understanding of algorithms, data structures, and AI techniques.

🚀 Projects
Real-time ML Model Deployment
Developed a Python project that deploys machine learning models to predict live data outputs with high accuracy.

LWT (Lightweight Technology) Python Application
Building a lightweight Python application aimed at optimizing resource usage on low-end hardware.

Research on AI-based Automation
Conducting research on automation using AI to streamline workflows in software projects.

🧰 Tech Stack
Category	Tools
Languages	
Libraries	
Tools	
🎯 Learning Goals
Master advanced Machine Learning algorithms

Build scalable real-time applications using Python

Contribute to open-source research projects in AI

Strengthen problem-solving skills with DSA & competitive programming

📊 GitHub Stats
🌐 Connect with Me
[
[
[
✉️ md3898145@gmail.com


name: Update GitHub Stats

on:
  schedule:
    - cron: '0 0 * * *'  
  workflow_dispatch:

jobs:
  update-readme:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout repo
        uses: actions/checkout@v3

      - name: Generate README stats and badges
        uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./public
