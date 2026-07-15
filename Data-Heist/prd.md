# PRD – Data-Heist

Version: 1.0
Author: Rashika K. Jain
Status: Planning and Develpoment

---

# Overview

Data-Heist is an interactive web-based game where users learn SQL and Data Analytics by solving realistic business problems instead of answering traditional quiz questions.

Players become junior data analysts working for different companies. Each mission presents a dataset, business problem, and objectives that require SQL queries, analytical thinking, and data visualization to solve.

The platform combines gamification, storytelling, AI assistance, and interactive dashboards to make learning SQL engaging and practical.

---

# Problem Statement

Most SQL learning platforms focus on syntax and isolated exercises.

Learners often know SQL commands but struggle to apply them to real-world business scenarios such as sales analysis, customer segmentation, fraud detection, and KPI reporting.

Data-Heist bridges this gap by simulating the workflow of a real data analyst.

---

# Goals

- Make SQL learning enjoyable.
- Simulate real analyst workflows.
- Teach business thinking, not only SQL.
- Improve analytical problem-solving.
- Build a portfolio-worthy learning experience.

---

# Target Audience

Primary

- Computer Science Students
- Data Science Students
- Data Analyst Aspirants
- Beginners learning SQL

Secondary

- Bootcamp students
- Working professionals refreshing SQL
- Recruiters exploring interactive learning tools

---

# Core Features

## Story-Based Missions

Users complete different business cases.

Examples

- E-commerce Sales Analysis
- Hospital Analytics
- Netflix Insights
- Bank Fraud Detection
- HR Analytics
- Food Delivery Analysis

Each mission contains

- Story
- Dataset
- Objectives
- SQL Challenges
- Final Report

---

## SQL Playground

Interactive SQL editor

Features

- Syntax highlighting
- Query execution
- Instant feedback
- Error explanations

---

## AI Assistant(if free api key is available if not skip for now)

AI helps users without giving direct answers.

Capabilities

- Explain SQL queries
- Explain errors
- Give hints
- Suggest optimization
- Convert SQL into plain English

---

## Interactive Dashboard(this is also mentioned in implementation plan which is good)

After each query

Automatically generate

- Charts
- KPIs
- Tables
- Insights

Visualization examples

- Bar Chart
- Pie Chart
- Line Graph
- Heatmap
- KPI Cards

---

## Level System

Intern

↓

Junior Analyst

↓

Business Analyst

↓

Senior Analyst

↓

Data Consultant

---

## Achievement System

Examples

🏆 First Query

🔥 10 Queries Without Errors

🧠 SQL Master

📊 Dashboard Expert

🚀 Case Completed

---

## XP System

Correct Query

+100 XP

Efficient Query

+50 XP

Fast Completion

+30 XP

Hint Used

-10 XP

---

## Leaderboard(let it be for v2)

Global ranking

Weekly ranking

Friends ranking

---

## User Dashboard

Track

- XP
- Level
- Completed Missions
- Accuracy
- SQL Streak
- Time Played

---

# Future Features(let it be for v2)

Multiplayer Challenges

Company Simulations

AI Generated Missions

Resume Certificate

Interview Mode

Custom Dataset Upload

Community Challenges

---

# Tech Stack

Frontend

- Next.js
- TypeScript
- Tailwind CSS
- Framer Motion

Backend

- FastAPI

Database

- PostgreSQL

ORM

- SQLAlchemy

Charts

- Plotly

Authentication(if needed for now or let it be for v2)

- Clerk/Auth.js

Deployment

- Vercel
- Railway

AI(optional)

- OpenAI API

---

# User Flow

Landing Page(should be good looking cool)

↓

Introduction of how our app is going to work

↓

Choose category what category case you wanna solve

↓
Choose Mission

↓

Read Story

↓

Explore Dataset

↓

Write SQL

↓

Run Query

↓

Receive Feedback

↓

Dashboard Updates

↓

Mission Complete

↓

Earn XP

↓

Unlock Next Mission

---

# Success Metrics

- Mission Completion Rate
- Average Session Time
- SQL Accuracy
- Daily Active Users
- User Retention
- Average Queries Executed

---

# Design Style(just dont make it another ai generated template shit looking visuals)

Modern

Dark Theme

Cyber + Data Visualization

Smooth Animations

Game UI

---

# Unique Selling Points

✅ Learn SQL through stories

✅ Real business datasets

✅ AI-powered learning assistant

✅ Interactive dashboards

✅ Gamified progression

✅ Portfolio-worthy projects

✅ Business-oriented learning

---

