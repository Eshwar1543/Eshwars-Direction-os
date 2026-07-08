Eshwar's Direction OS
Product Requirements Document (PRD)

Version: 0.1 Alpha

Status: Draft

Author: Eshwar Prasad

Chief Product Architect: ChatGPT

Last Updated: July 2026

Table of Contents
1. Executive Summary
2. Vision
3. Mission
4. Product Philosophy
5. Problem Statement
6. Product Goals
7. Success Metrics (OKRs)
8. User Personas
9. Jobs To Be Done
10. Product Principles
11. Scope
12. Out of Scope
13. Functional Requirements
14. Non-Functional Requirements
15. User Journeys
16. Information Architecture
17. Module Specifications
18. Data Model
19. Permission Model
20. AI Strategy
21. Analytics Strategy
22. Security
23. Technology Stack
24. Risks
25. MVP
26. Roadmap
27. Appendix
1. Executive Summary
Product Name

Eshwar's Direction OS

Product Type

Personal Operating System

Category

Performance Management + Creative Workflow + AI Productivity + Film Development Platform

Target Platform
macOS
Windows
iPad (Future)
iPhone (Future)
Web
Product Vision

Eshwar's Direction OS is a personal operating system that transforms disciplined daily execution into long-term professional mastery by integrating filmmaking, editing, AI, freelancing, business operations, and continuous performance analytics into one unified environment.

One-Line Mission

Reduce friction between learning, creating, and earning.

North Star

Help Eshwar become a world-class film director.

Everything in the product must support this goal.

2. Vision

The operating system is not a productivity app.

It is a decision-making system.

When opened, it answers:

What should I work on today?
What skill is weakest?
What project moves me closer to directing films?
What is preventing me from getting my first client?
What should I improve before tomorrow?
3. Mission

The application exists to:

Improve editing ability
Improve storytelling
Build a portfolio
Build a freelancing business
Use AI effectively
Prepare for film direction
Measure progress objectively
4. Product Philosophy

Every feature must satisfy at least one of these principles.

Principle 1 — Execution over Organization

The software exists to increase completed work, not organize endless tasks.

Principle 2 — One Source of Truth

Information should exist only once and be connected through relationships.

Principle 3 — Data Before Emotion

Progress is measured through evidence.

Examples:

Editing hours
Portfolio growth
Client outreach
Revenue
Skill practice
Principle 4 — Low Cognitive Load

The application should reduce thinking about the system itself.

The user should think about filmmaking.

Principle 5 — Build Professional Habits

The product should encourage:

Daily execution
Reflection
Deliberate practice
Review
Shipping work
5. Problem Statement

Today's creative workflow is fragmented.

Learning happens in YouTube.

Ideas live in Notes.

Tasks live in Notion.

Projects live in folders.

Portfolio lives elsewhere.

AI prompts disappear.

Client tracking is manual.

There is no unified system that connects these activities.

6. Product Goals
Primary Goal

Become a professional film director.

Secondary Goal

Become a high-income freelance editor.

Third Goal

Develop an AI-first workflow.

Success Definition

The product succeeds if it measurably improves:

Editing quality
Portfolio quality
Client acquisition
Revenue
Decision making
Consistency
7. Success Metrics (OKRs)
Objective 1

Become a professional editor.

Key Results
300 editing hours
10 portfolio projects
20 recreation projects
80% hireability score
Objective 2

Acquire freelance clients.

Key Results
1 first client
20 outreach messages
5 discovery calls
Positive client feedback
Objective 3

Become AI-first.

Key Results
Prompt library established
AI used in every project where appropriate
Reusable workflows documented
8. User Persona
Primary User

Eshwar Prasad

Profile:

Engineering student
Aspiring film director
Professional editor in training
AI-first creator
Solo founder
Pain Points
Inconsistent execution
Portfolio gaps
Weak outreach
Decision fatigue
Scattered knowledge
Perfectionism
Goals
Master editing
Build professional portfolio
Earn freelance income
Direct films
Use AI as leverage
9. Jobs To Be Done

When I begin my day,

I want to know:

What matters most today
What project to ship
Which skill needs practice
Whether I'm improving

So that:

I make measurable progress toward becoming a professional filmmaker.

# 10. Product Principles

Every feature inside Eshwar's Direction OS must follow these principles.

---

## Principle 1 — Execution First

The application exists to increase completed work, not completed tasks.

Success is measured by:

- Hours edited
- Portfolio shipped
- Skills improved
- Clients acquired

---

## Principle 2 — Simplicity

Every screen should answer one question.

If a screen tries to solve multiple unrelated problems, split it.

---

## Principle 3 — Single Source of Truth

Every piece of information should exist only once.

Example:

A Portfolio Project should not duplicate:

- Editing Hours
- Skills
- Daily Logs

Instead, everything should be connected through relationships.

---

## Principle 4 — Measure Everything

The application should collect measurable data.

Examples:

- Editing Hours
- Deep Work Hours
- Portfolio Count
- Revenue
- Skill Progress
- Consistency

---

## Principle 5 — AI as a Force Multiplier

AI should never replace thinking.

AI should:

- Accelerate research
- Improve quality
- Reduce repetitive work
- Generate ideas
- Review work

---

# 11. Scope

Version 1 focuses only on becoming a better editor and future film director.

Modules included:

- Mission Control
- Daily Logs
- Portfolio
- Skills
- Learning
- Analytics
- AI Center

---

# 12. Out of Scope

The following features are intentionally excluded.

- Social Media
- Messaging
- Calendar Replacement
- Habit Tracking unrelated to filmmaking
- Music Player
- Weather
- News
- Chat System
- Team Collaboration

Reason:

These features do not directly improve filmmaking capability.

---

# 13. Product Modules

The application consists of seven core modules.

---

## Module 1

Mission Control

Purpose

Provide complete visibility into today's priorities.

Responsibilities

- Daily Mission
- Today's Tasks
- Progress
- KPIs
- Alerts

---

## Module 2

Director Academy

Purpose

Manage learning.

Tracks

- Editing
- Storytelling
- Direction
- Cinematography
- Sound Design
- Color
- AI

---

## Module 3

Studio

Purpose

Manage creative work.

Contains

- Portfolio
- Practice Projects
- Client Work
- Short Films
- Film Experiments

---

## Module 4

AI Lab

Purpose

Centralize every AI workflow.

Contains

- Prompt Library
- Prompt Templates
- Research
- Script Generation
- Feedback

---

## Module 5

Business

Purpose

Manage freelancing.

Contains

- Clients
- Leads
- Revenue
- Invoices
- Pricing
- Contracts

---

## Module 6

Knowledge Vault

Purpose

Store reusable knowledge.

Contains

- Film Analysis
- Editing Notes
- References
- Books
- Lessons

---

## Module 7

Analytics

Purpose

Measure performance.

Tracks

- Editing Hours
- Consistency
- Skill Growth
- Revenue
- Portfolio Growth
- Learning Progress

---

# 14. Navigation

Primary Navigation

Mission Control

↓

Director Academy

↓

Studio

↓

AI Lab

↓

Business

↓

Knowledge Vault

↓

Analytics

↓

Settings

---

# 15. User Journey

Morning

↓

Mission Control

↓

Today's Mission

↓

Deep Work

↓

Daily Log

↓

Portfolio Update

↓

Analytics Review

↓

Reflection

This becomes the default workflow every day.
# 16. Functional Requirements

This section defines the behavior of every major module.

---

# 16.1 Mission Control

## Purpose

Mission Control is the home screen.

The user should understand the entire day within five seconds.

---

## Functional Requirements

The dashboard shall display:

- Current Date
- Current Sprint
- Day Progress
- Current Mission
- Today's Tasks
- Deep Work Progress
- Editing Hours
- Portfolio Progress
- Current Skill Level
- Hireability Score
- Red Alerts
- Upcoming Deadlines

---

## User Actions

The user can

- Create Mission
- Complete Mission
- Start Deep Work Session
- Open Portfolio
- Open Daily Log
- Open Analytics

---

## KPIs

Display

- Today's Hours
- Weekly Hours
- Monthly Hours
- Projects Completed
- Skills Practiced
- Consistency Streak

---

# 16.2 Daily Logs

## Purpose

Record measurable progress every day.

---

## Required Fields

Date

Mission

Editing Hours

Deep Work Hours

Focus Score

Energy

Mood

Distractions

Biggest Win

Biggest Mistake

Lessons Learned

Tomorrow Priority

Reflection

---

## Functional Behavior

One log per day.

Logs cannot be duplicated.

Logs are searchable.

Logs contribute to Analytics.

---

# 16.3 Portfolio

## Purpose

Track every editing project.

---

## Project Fields

Project Name

Category

Difficulty

Client

Duration

Hours Invested

Completion Date

Status

Feedback

Thumbnail

Project Link

Revision Count

Final Score

---

## Status

Planned

In Progress

Review

Completed

Published

Archived

---

## User Actions

Create Project

Edit Project

Archive Project

Duplicate Project

Export Project Data

---

# 16.4 Skills

Purpose

Measure deliberate practice.

---

## Skill Categories

Editing

Storytelling

Sound Design

Color

Typography

Motion Graphics

Direction

Writing

Communication

Client Management

AI

---

## Every Skill Tracks

Level

Hours Practiced

Last Practiced

Weaknesses

Strengths

Projects Using Skill

Growth Trend

---

# 16.5 Learning

Purpose

Manage education.

---

Tracks

Books

Courses

Tutorials

Film Analysis

Masterclasses

Practice Sessions

---

Each Lesson Stores

Source

Instructor

Duration

Key Takeaways

Application Status

Practice Project

Mastery Score

---

# 16.6 Analytics

Purpose

Visualize progress.

---

Charts

Editing Hours

Portfolio Growth

Skill Growth

Revenue

Consistency

Learning Progress

---

Analytics Periods

Daily

Weekly

Monthly

Quarterly

Yearly

---

# 16.7 AI Center

Purpose

Centralize AI workflows.

---

Contains

Prompt Library

Workflow Templates

Script Generator

Idea Generator

Shot List Generator

Feedback Assistant

Research Assistant

Storyboard Assistant

---

# 16.8 Settings

Purpose

Configure the application.

---

Contains

Theme

Notifications

Goals

Profile

GitHub

AI Keys

Export Data

Backup

Restore

# 17. Database Architecture

## Overview

The application uses a relational database.

Database Engine:

PostgreSQL

Backend:

Supabase

Architecture Principles

- Single Source of Truth
- No duplicated data
- Every table has a primary key
- Relationships over duplication
- Soft delete whenever possible

---

# Core Tables

Version 1 contains the following tables.

1. users
2. daily_logs
3. missions
4. projects
5. skills
6. learning
7. ai_prompts
8. analytics
9. settings

---

# users

Purpose

Store profile information.

Fields

id

name

email

avatar

created_at

updated_at

---

# daily_logs

Purpose

Track daily execution.

Fields

id

date

mission

editing_hours

deep_work_hours

focus_score

energy

mood

biggest_win

biggest_mistake

reflection

tomorrow_priority

created_at

updated_at

---

# missions

Purpose

Track active objectives.

Fields

id

title

description

priority

status

deadline

completed_at

created_at

updated_at

---

# projects

Purpose

Portfolio management.

Fields

id

title

category

status

difficulty

client

duration

editing_hours

thumbnail

project_link

feedback_score

revision_count

published

created_at

updated_at

---

# skills

Purpose

Measure deliberate practice.

Fields

id

name

category

level

hours_practiced

last_practiced

growth_rate

created_at

updated_at

---

# learning

Purpose

Learning management.

Fields

id

title

type

source

instructor

duration

mastery_score

applied

notes

created_at

updated_at

---

# ai_prompts

Purpose

Store reusable prompts.

Fields

id

title

category

prompt

model

favorite

created_at

updated_at

---

# analytics

Purpose

Store calculated metrics.

Fields

id

editing_hours

portfolio_score

hireability_score

streak

consistency

skill_growth

updated_at

---

# settings

Purpose

Application configuration.

Fields

id

theme

accent_color

goal_hours

goal_projects

notifications

updated_at

---

# Relationships

users

↓

daily_logs

users

↓

missions

users

↓

projects

projects

↓

skills

projects

↓

learning

daily_logs

↓

projects

daily_logs

↓

missions

skills

↓

analytics

projects

↓

analytics

---

# Database Rules

Every table uses UUID as primary key.

Every table contains:

created_at

updated_at

Every foreign key uses cascading updates.

No duplicate records.

Soft delete for future versions.

---

# Version 1 Database Size

Expected Records

Daily Logs

365+

Projects

100+

Learning

500+

Skills

50+

AI Prompts

500+

Analytics

Unlimited
