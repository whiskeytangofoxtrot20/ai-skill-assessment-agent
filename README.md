# AI-Powered Skill Assessment & Personalized Learning Agent

## Problem Statement
Resumes only show claimed skills, not real proficiency. This system evaluates actual skill level and generates a personalized learning plan.
AI-Powered Skill Assessment & Personalised Learning Plan Agent: A resume tells you what someone claims to know - not how well they actually know it. Build an agent that takes a Job Description and a candidate's resume, conversationally assesses real proficiency on each required skill, identifies gaps, and generates a personalised learning plan focused on adjacent skills the candidate can realistically acquire - with curated resources and time estimates with some rules

## Solution
This project uses an AI-based workflow to:
- Compare Job Description with Resume
- Assess real skill proficiency
- Identify skill gaps
- Generate structured learning roadmap with time estimates and resources

## System Flow
Google Form → Google Sheets → ChatGPT (Prompt Engine) → Output Stored in Sheets

## How It Works
1. User submits Job Description and Resume via Google Form
2. Data is stored in Google Sheets
3. AI prompt processes the input manually in ChatGPT
4. Output (skill analysis + learning plan) is copied back into the sheet

## Features
- Skill extraction from job descriptions
- Resume skill evaluation
- Gap analysis
- Personalized learning roadmap

## Limitations

- No fully automated backend due to lack of paid API integration
- AI execution is manually triggered in ChatGPT
- Designed as functional prototype, not production system

## Tools Used
- Google Forms (input interface)
- Google Sheets (data storage)
- ChatGPT (AI reasoning engine)

## Live Prototype
Google Form: [https://forms.gle/v6Fr5JbZZwViwADT7]

## Demo Output
Check sample rows in Google Sheet for AI-generated results. Google Sheets Link: [https://docs.google.com/spreadsheets/d/12iztjRiyXnE97GGZ0PgeK0nO3DYpsekTpRQqMNpVrxE/edit?usp=sharing]

## Note
This project is implemented as a working prototype using freely available tools (Google Forms, Google Sheets, and ChatGPT). Full end-to-end automation and production-grade deployment (including real-time AI API integration and no-code deployment platforms like Glide automation features) may require paid subscriptions or API-based services, which are not feasible within the current hackathon constraints and without external investment. Therefore, the current implementation demonstrates the complete functional workflow using a semi-manual AI processing approach while maintaining the intended system design and output quality. Manually things have to be setup in the timeframe and available budget.
