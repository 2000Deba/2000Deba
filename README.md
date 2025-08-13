<p align="center">
  <img src="https://capsule-render.vercel.app/api?text=Hey%20There!%20I’m%20Naman%20Khandelwal&animation=waving&color=gradient&height=100" />
</p>

<h3 align="center">A passionate Full‑Stack Developer and Life‑Long Learner based in India 🇮🇳</h3>

<p align="center">
  <a href="https://portfolio-namank.vercel.app" target="_blank">Portfolio</a> •
  <a href="https://www.linkedin.com/in/naman-khandelwal-568971189/" target="_blank">LinkedIn</a> •
  <a href="mailto:namankoolwal1411@gmail.com">Email me</a>
</p>

---

## 🧠 About Me

- 💻 I’m currently working with: **Next.js, MongoDB, Tailwind CSS**
- 🌱 Learning ➤ **Three.js, Advanced MERN Stack**
- ⚡ Fun Fact: I’m secretly Spiderman 🕷️ (don’t tell anyone!)

---

## 🛠️ Languages and Tools

<p align="center">
  <!-- Add shields for your tech stack -->
  ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
  ![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react)
  ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=nextdotjs)
  ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=nodedotjs)
  ![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css)
  ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat&logo=mongodb)
</p>

---

## 📌 Featured Projects

| Project                  | Description                                       | Link                          |
|--------------------------|---------------------------------------------------|-------------------------------|
| Get Me A Chai            | Crowdfunding platform using Next.js & MongoDB      | https://get-me-chai.vercel.app |
| Pinterest‑Backend        | Pinterest clone backend with Node.js & MongoDB     | GitHub Repo + Live Link       |
| Ochi‑design              | React + Tailwind modern portfolio UI project       | GitHub Repo                    |

---

## 📊 GitHub Stats & Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=namankoolwal&show_icons=true&theme=radical" alt="GitHub Stats" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=namankoolwal&layout=compact&theme=radical" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=namankoolwal&style=flat" alt="Profile Views" />
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com?user=namankoolwal&theme=radical" alt="GitHub Streak" />
</p>

---

## 🐍 Contribution Snake

```yaml
# .github/workflows/snake.yml
name: Snake Animation
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
jobs:
  snake:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: namankoolwal
          outputs: |
            dist/github-contribution-grid-snake.svg
      - name: Deploy to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
