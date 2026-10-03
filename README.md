# Jangwon Lee

**Software developer who finishes what he starts, and builds for problems people actually have.**

Software Science @ Dankook University · Applying for internships in H2 2027

📫 [ljw.jang05@gmail.com](mailto:ljw.jang05@gmail.com) · 📄 [Portfolio (Notion)](https://app.notion.com/p/175baeee09d480b58b89dfb6dc1bce54?source=copy_link) · ✍️ [Blog](https://manor-1.tistory.com/)

---

## About

I started programming with Entry in middle school. Curiosity about what was under the blocks never went away. Today I care about one thing in particular: **applying AI where it makes a product genuinely more useful**, not bolting it on as a feature.

- 🔭 Returning for my 3rd year, targeting internship applications for H2 2027
- 🌱 Exploring how AI fits meaningfully into real, usable products
- 🏆 1st place, 60-person overnight hackathon (team lead, 2023)

---

## Featured Project

### [ISIG](https://resplendent-dodol-5e10ec.netlify.app/) — AI-powered handoff documentation tool

When the person who knows how something works leaves, the knowledge usually leaves with them, and the notes they write are almost always incomplete.

ISIG **interviews you**. You describe your task in plain language, the AI asks the follow-up questions a good manager would (What's the exception case? What's easy to get wrong? What comes next?), and the conversation becomes a checklist document someone else can actually execute from.

<!-- Add a screenshot: <img src="./isig-screenshot.png" width="100%" /> -->

**Features**
- Adaptive interview that shapes each question around your last answer
- Auto-generated, checklist-style handoff document
- Shareable links, in-place editing, print/PDF export with traceable watermarking
- Google auth with per-user data isolation via Postgres Row Level Security

**Stack**: Next.js (App Router) · Supabase (Postgres, Auth, RLS) · Google Gemini API · Netlify

**Engineering decisions**
- Every table is RLS-locked to its owner by default; the single public read path (shared links) goes through a single-purpose `SECURITY DEFINER` function instead of opening the table.
- API routes verify the Supabase session token server-side, so the AI endpoints are not protected by a login screen alone.
- Built entirely in GitHub Codespaces, including handling a mid-development model deprecation and rebuilding the auth flow after a repository migration.

---

## Other Projects

| Project | Description | Role |
|---|---|---|
| **PS Auto Creator** | Automates weekly tiered Baekjoon problem sets: samples from the Solved.ac API with filters (≤10,000 solvers, not used in the last 48 rounds), then creates the group practice through Selenium. Python · MongoDB · CRON | Full logic development (2-person team) |
| **Neis Improvement Platform** 🏆 | Redesigned attendance and anonymous-complaint features of a school system. 1st place at a 60-person hackathon. HTML · CSS · JS | Team lead, attendance & complaint pages |
| **Farm Subscription Platform** | Subscription and crop management with real-time sync across devices | Firebase schema design |
| **Task Manager** | Java member/work management system with DTO pattern, JDBC and REST endpoints | Backend & frontend |

---

## Skills

<p>
  <img src="https://img.shields.io/badge/TypeScript-0F8477?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-0F8477?style=flat-square&logo=javascript&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-0F8477?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-0F8477?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-0F8477?style=flat-square&logo=openjdk&logoColor=white" />
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
  <img src="https://img.shields.io/badge/Netlify-14171F?style=flat-square&logo=netlify&logoColor=00C7B7" />
</p>

---

## Experience

**Expotential**: Full-time Member · Apr 2025 – Present
Rotated through planning and research on multiple client projects; acted as interim team lead for about a month.

**Software & Algorithm Club (SWAG)**: Executive Member, Operating Team · Mar 2024 – Jun 2025
Ran a 9-week data structures seminar series with self-authored materials; designed and delivered two rounds of a beginner C track; built and maintained the club's Notion operating system for the 3rd generation.

## Education

Dankook University, Software Science (Mar 2024 – Present)

## Problem Solving

[solved.ac](https://solved.ac/profile/jw19) · [Codeforces](https://codeforces.com/profile/ljw.jang05) · [AtCoder](https://atcoder.jp/users/jw19)
