import datetime

username = "shrutichauha7"

readme = f"""
<h1 align="center">Hi 👋, I'm Shruti Chauhan</h1>
<h3 align="center">AI/ML Enthusiast | Data Scientist</h3>

---

## 🚀 About Me
- 🔭 Working on AI & ML Projects  
 

---

---

## 📈 GitHub Stats
![Stats](https://github-readme-stats.vercel.app/api?username={username}&show_icons=true&theme=radical)

---

## 🔥 Streak Stats
![Streak](https://streak-stats.demolab.com/?user={username}&theme=radical)

---

## 🌟 Quote of the Day
> "Code. Learn. Repeat."  

---

## 📅 Last Updated
{datetime.datetime.now()}
"""

with open("README.md", "w", encoding="utf-8") as f:
    f.write(readme)

print("README generated successfully!")
