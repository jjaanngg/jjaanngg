<div align="center">
  <img src="./banner.png" width="100%" alt="Jangwon Lee" />
</div>

<br/>

I care about finishing what I start, and about building things that solve a problem someone actually has — not just things that demonstrate a skill.

I was introduced to programming through Entry in middle school. Block-based logic turned into curiosity about what was happening underneath, and that curiosity hasn't really stopped since.

I'm still figuring out exactly what kind of developer I want to be. What I do know: building [ISIG](#featured-project) was the most engaged I've been in a project so far, and it's sharpened a specific interest — not AI as a feature to bolt on, but AI applied where it makes a product genuinely more useful.

- 🔭 Returning to my 3rd year of study soon, targeting internship applications for the second half of 2027
- 🌱 Exploring how AI fits meaningfully into real, usable products
- 📫 [ljw.jang05@gmail.com](mailto:ljw.jang05@gmail.com)

---

## Featured Project

### [ISIG](https://isig.vercel.app) — AI-powered handoff documentation tool

Most work that gets learned by doing is hard to explain in words. When the person who knows how something works leaves, the knowledge usually leaves with them — the handoff notes people manage to write are almost always incomplete.

ISIG interviews you. You describe your task in plain language, the AI asks the follow-up questions a good manager would (what's the exception case, what's easy to get wrong, what comes next), and the conversation becomes a checklist document someone else can actually execute from — not just read.

<!-- 여기에 실제 ISIG 스크린샷 하나 넣으세요. 예: <img src="./isig-screenshot.png" width="100%" /> -->

**What it does**
- Conversational interview that adapts its next question to what you just said, instead of a fixed form
- Auto-generates a structured, checklist-style handoff doc from the conversation
- Shareable links, in-place editing, print/PDF export with traceable watermarking
- Google auth with per-user data isolation via Postgres Row Level Security

**Stack**: Next.js (App Router) · Supabase (Postgres, Auth, RLS) · Google Gemini API · Vercel

**Engineering decisions worth mentioning**
- Every table is RLS-locked to its owner by default; the one public read path (shared doc links) goes through a single-purpose `SECURITY DEFINER` function instead of opening the table
- API routes verify the Supabase session token server-side — the AI endpoints aren't just gated by a login screen
- Built and iterated entirely from a browser-based dev environment (GitHub Codespaces), including chasing down a mid-development model deprecation and rebuilding the auth flow around a repo migration mid-project

---

## Other Projects

| Project | Description | Role |
|---|---|---|
| **Farm Subscription Platform** | Subscription & crop management system with real-time sync across devices | Firebase schema design |
| **Task Manager** | Java member/work management system — DTO pattern, JDBC, REST endpoints | Backend & frontend |
| **PS Auto Creator** | Auto-generates tiered Baekjoon problem sets weekly via Solved.ac API + Selenium, posts to a BOJ group | Full logic development |

---

## Skills

<p>
  <img src="https://img.shields.io/badge/TypeScript-0F8477?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-0F8477?style=flat-square&logo=javascript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-0F8477?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-0F8477?style=flat-square&logo=cplusplus&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/React-14171F?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-14171F?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React_Native-14171F?style=flat-square&logo=react&logoColor=61DAFB" />
</p>
<p>
  <img src="https://img.shields.io/badge/Node.js-14171F?style=flat-square&logo=nodedotjs&logoColor=339933" />
  <img src="https://img.shields.io/badge/Supabase-14171F?style=flat-square&logo=supabase&logoColor=3ECF8E" />
  <img src="https://img.shields.io/badge/PostgreSQL-14171F?style=flat-square&logo=postgresql&logoColor=4169E1" />
  <img src="https://img.shields.io/badge/MongoDB-14171F?style=flat-square&logo=mongodb&logoColor=47A248" />
  <img src="https://img.shields.io/badge/Firebase-14171F?style=flat-square&logo=firebase&logoColor=FFCA28" />
</p>
<p>
  <img src="https://img.shields.io/badge/Git-14171F?style=flat-square&logo=git&logoColor=F05032" />
  <img src="https://img.shields.io/badge/Docker-14171F?style=flat-square&logo=docker&logoColor=2496ED" />
  <img src="https://img.shields.io/badge/Vercel-14171F?style=flat-square&logo=vercel&logoColor=white" />
</p>

## Experience

**Software & Algorithm Club (SWAG)** — Executive Member, Operating Team · Mar 2024 – Jun 2025
Ran weekly data structures seminars for an assigned group; designed and delivered two rounds of a beginner C track; built and maintained the club's Notion operating system for the 3rd generation.

**Expotential** — Full-time Member · Apr 2025 – Present
Rotated through planning and research on multiple client projects; acted as interim team lead for about a month.

## Education

Dankook University — Software Science (Mar 2024 – Present)

## Problem Solving

[solved.ac](https://solved.ac/profile/jw19) · [Codeforces](https://codeforces.com/profile/ljw.jang05) · [AtCoder](https://atcoder.jp/users/jw19)

---

<img src="https://github-readme-stats.vercel.app/api?username=jjaanngg&show_icons=true&hide_border=true&title_color=0F8477&icon_color=0F8477&text_color=8B93A7&bg_color=14171F" width="48%" />
