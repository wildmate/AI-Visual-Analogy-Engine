# 🏛 AI Visual Analogy Engine

An institutional AI-powered tool that transforms scientific definitions into structured visual analogies using Google Gemini API.

## Deployment Model

This project follows a dual-deployment strategy:

1. **GitHub Repository** – Ensures transparency and reproducibility.
2. **Live Deployment (shinyapps.io)** – Provides real-time interactive access.

## Features

- Tiered computational modes:
  - Demo Version
  - Basic Live (Text Only)
  - Advanced (Text + Image)
  - Pro Reasoning Mode
- Automatic quota-aware fallback
- Usage counter and quota indicator
- Institutional branding
- HTML and PDF export

## Architecture

User Input → Shiny App → Gemini API → Structured Output → Optional Image Rendering → Export

## Security

API keys are managed securely using environment variables and are not stored in the repository.

## Deployment

Live version available at:
(https://visual-analogy-creator.shinyapps.io/visual_analogy_creator/)


## Developed By

Sunil Kumar Birua
PhD Research Scholar  
Department of Chemical Biotechnology
SASTRA Deemed To be University
