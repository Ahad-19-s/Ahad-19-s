# Hi there 👋, I'm Ahad✨

### Student @ IIT, Jahangirnagar University | 

---

## About Me

  * Studying Information Technology @ IIT-JU (2024 batch)
  * Learning Web Dev, DSA , UI/UX,ML
  * ‍ Building mini-projects & exploring GitHub
  * Open to collaboration & teamwork

---

## ⚡ Tech Stack

---

## GitHub Stats

![github stats image 1]()
![github stats image 2]()
![github streak image]()

---

## Achievements

![achievements image]()

---

## Activity Graph

![activity graph image]()

---

## Connect With Me

![social icon 1]() ![social icon 2]() ![social icon 3]()

---

## Fun Facts

  * I code best with lo-fi music
  * Passionate about UI design
  * Love nature photography
  * Enjoy logic puzzles & brain teasers

---

## Popular repositories

  1. firstRep — firstRep (Public)
  2. ICT-2106-Internet-and-web-technology-lab (Public) — HTML
  3. projects (Public)
  4. afrozaema (Public) — Personal GitHub profile of Afroza Ema – Student at IIT, Jahangirnagar University | Passionate about coding, design, and building cool things on the web.
  5. afrozaema.github.io (Public) — Afroza Ema's personal portfolio – Showcasing projects, skills & journey from IIT JU
  6. SeatFinder (Public) — An AI-powered exam seat finder and direction guide for Jahangirnagar University students | ema — TypeScript
efficiency.	Python, Pandas, Scikit-learn
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




