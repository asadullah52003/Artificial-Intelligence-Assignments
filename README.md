🤖 ARTIFICIAL INTELLIGENCE

🧠 Welcome to the AI Lab
This repository contains my Artificial Intelligence coursework and practical assignments for BSCS 6C.

# Assignment 1: CleanBot – Intelligent Vacuum Cleaner Agent

## Introduction

CleanBot is an intelligent vacuum cleaner robot that uses sensors to detect dirt and obstacles. It can move around the room, avoid obstacles, vacuum the floor, and make decisions to keep the area clean.

## Environment Types

| Property | Type |
|---|---|
| Observability | Partially Observable |
| Determinism | Stochastic |
| Episodes | Sequential |
| Change | Dynamic |
| Values | Continuous |
| Agents | Multi-Agent |

## PEAS Framework

| Component | Description |
|---|---|
| **P – Performance** | Clean floor, efficient cleaning |
| **E – Environment** | Rooms, floors, furniture |
| **A – Actuators** | Wheels, brushes, vacuum motor |
| **S – Sensors** | Dirt, obstacle, and distance sensors |

## Agent Working

CleanBot uses sensors to collect information about its environment. Based on the sensor information, it decides where to move, avoids obstacles, and cleans dirty areas.

---

# Assignment 2: Travel Agent in Python

## Description

The Travel Agent is a simple Python-based program that collects the user's travel information and recommends a suitable hotel and transportation based on the given budget.

## Features

- Takes user's name
- Takes preferred destination
- Takes travel budget
- Takes number of days
- Recommends a suitable hotel
- Recommends suitable transportation

## Technology Used

- **Python**
- **Google Colab**

## How It Works

The program uses `if-elif-else` conditions to select a hotel and transportation according to the user's budget.

### Budget-Based Recommendation

| Budget | Hotel | Transport |
|---|---|---|
| Less than $500 | Budget Hotel | Public Transport |
| $500 – $999 | Standard Hotel | Bus / Train |
| $1000 or more | Luxury Hotel | Flight / Private Transport |

## Conclusion

These assignments demonstrate basic concepts of Artificial Intelligence agents and rule-based decision making using Python.
