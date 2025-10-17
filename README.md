👋 Hi, I’m Md Ahad Ali
🎓 2nd Year Undergraduate | Institute of Information Technology (IIT), Jahangirnagar University
🤖 Passionate about Machine Learning, Research & Real-time Python Projects
✨ Lifelong learner driven by curiosity and problem solving

<p align="center"> <img src="https://raw.githubusercontent.com/mdahadali/mdahadali/main/assets/ahad-animated-banner.gif" alt="Md Ahad Ali Banner" width="700" /> </p>
🌟 About Me
I am a motivated Computer Science student with a deep interest in Machine Learning, AI research, and developing impactful real-time Python applications. My focus is on bridging theory with hands-on projects that solve practical problems.

📚 Currently mastering Data Structures & Algorithms and Machine Learning

💻 Building Python projects that address real-world challenges

🏆 Solved 350+ problems on competitive programming platforms like LeetCode and Codeforces

🤝 Actively seeking collaborations on open-source AI and ML projects

🚀 Selected Projects
Project Name	Description	Tech Stack
Real-time ML Model Deployment	Deploys live machine learning models for accurate predictions on streaming data.	Python, Flask, TensorFlow
LWT Python Application	Lightweight app optimized for resources on low-end systems.	Python
AI-driven Workflow Automation	Research-driven project automating tasks via AI algorithms to enhance efficiency.	Python, Pandas, Scikit-learn
🧰 Tech Stack
🎯 Learning Goals
Build advanced scalable ML models for real-time data analysis

Contribute to impactful open-source AI projects

Improve coding practices and collaboration efficiency

Explore integration of AI into daily tools and automation workflows

📊 GitHub Stats
🌐 Connect with Me
[
[
[
✉️ md.ahad@example.com




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




