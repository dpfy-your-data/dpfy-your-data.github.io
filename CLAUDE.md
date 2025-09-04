# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for the ICML 2025 tutorial "DP-fy your DATA: How to (and why) synthesize Differentially Private Synthetic Data" by Natalia Ponomareva, Sergei Vassilvitskii, Peter Kairouz, and Alex Bie.

## Development Commands

- `npm run dev` or `npm run serve`: Start local development server on port 8000
- `npm run build`: No build needed for static site

## Project Structure

- `index.html`: Main website page
- `styles.css`: CSS styling with academic serif typography
- `package.json`: Project metadata and scripts
- `new.png`: Custom NEW graphic for announcements

## Design System

### Typography
- **Font**: Times, Times New Roman, serif (academic style)
- **Base text**: 1.1rem for consistent readability
- **Headings**: ALL CAPS with red accent color (#d73027)
- **Links**: Red (#d73027) with hover effects (#b52017)

### Color Palette
- **Primary text**: #333 (dark gray)
- **Accent color**: #d73027 (red for headings and links)
- **Hover color**: #b52017 (darker red)
- **Background**: White with light gray (#f8f9fa) for announcement boxes

### Layout Sections
1. **Header**: Title, event info, authors, Vancouver Convention Center image
2. **Resources**: Survey announcement with NEW graphic + 3-column resource table (Recording, Slides, Demo)
3. **Abstract**: Tutorial description (2 paragraphs)
4. **Contact**: Email contact information

## Content Management

### Key Links to Update
- Recording: https://icml.cc/virtual/2025/40009 (already set)
- Slides PDF: Replace `href="#"` with actual PDF link
- Demo Colab: Replace `href="#"` with Colab notebook link  
- Survey article: Replace `href="#"` with arxiv link

### Resource Table Structure
- 3-column layout with consistent styling
- Each cell contains: emoji + title link + descriptive subtitle
- Bordered with vertical dividers and outer border

### Visual Elements
- Vancouver Convention Center image from ICML website
- Custom new.png graphic for announcements
- Red accent borders on announcement boxes
- Consistent spacing and typography throughout

## Style Guidelines
- Maintain academic, professional appearance
- Use consistent 1.1rem font size for all body text
- Keep ALL CAPS for section headings
- Use red accent color sparingly for emphasis
- Ensure proper contrast and readability