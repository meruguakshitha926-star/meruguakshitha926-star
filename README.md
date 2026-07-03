from pathlib import Path
from pypandoc import convert_text

md = r"""# Hi 👋, I'm Akshitha Merugu

<h3 align="center">Computer Science Student | Passionate about AI, Machine Learning & Software Development</h3>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=220&section=header&text=Akshitha%20Merugu&fontSize=45&fontColor=ffffff"/>
</p>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Poppins&size=24&duration=3000&pause=1000&center=true&vCenter=true&width=700&lines=Computer+Science+Student;AI+%26+Machine+Learning+Enthusiast;Software+Development;Always+Learning+New+Technologies"/>
</p>

---

## 👩‍💻 About Me

- 🎓 **B.Tech CSE** @ MRECW
- 📍 Andhra Pradesh, India
- 🌱 Learning: Machine Learning, Deep Learning, NLP, Transformers, Generative AI
- 💡 Interested in AI, Software Development & Problem Solving
- 📧 **meruguakshitha926@gmail.com**

---

## 🌐 Connect with Me

<p>
<a href="https://www.linkedin.com/in/akshitha-merugu-7a677632a/">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:meruguakshitha926@gmail.com">
<img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
</p>

---

## 🚀 Tech Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=python,java,c,html,css,react,tailwind,fastapi,postgres,mysql,git,github,vscode,tensorflow,pytorch"/>
</p>

**AI/ML:** NumPy • Pandas • Scikit-Learn

---

## 🚀 Featured Projects

- 🛠 **Issue Tracker Pro**
- 🚖 **Online Cab Booking System**
- ✍ **Signature App**
- 👨‍🏫 **One-to-One Mentor Platform**
- 🏡 **HomeWorth (Hackathon Project)**
- 🌧 **Smart Drainage Monitoring System**

---

## 📊 GitHub Stats

<p align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=meruguakshitha926-star&show_icons=true&theme=tokyonight"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=meruguakshitha926-star&layout=compact&theme=tokyonight"/>
</p>

## 🔥 GitHub Streak

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=meruguakshitha926-star&theme=tokyonight"/>
</p>

## 📈 Contribution Graph

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=meruguakshitha926-star&theme=tokyo-night"/>
</p>

## 👀 Profile Views

<p>
<img src="https://komarev.com/ghpvc/?username=meruguakshitha926-star&label=Profile%20Views&style=flat-square"/>
</p>

## 💡 Quote

> **"Learning never exhausts the mind." — Leonardo da Vinci**

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4facfe,100:00f2fe&height=120&section=footer"/>
</p>
"""
out="/mnt/data/README.md"
convert_text(md,"md",format="md",outputfile=out,extra_args=["--standalone"])
print(out)

