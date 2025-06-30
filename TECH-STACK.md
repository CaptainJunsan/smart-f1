# 🧰 Tech Stack – Smart F1

This document outlines the core tools, services, and technologies used to build **Smart F1**, a custom-designed Formula 1 data explorer powered by OpenF1 API and optional AI assistance.

---

## 🔧 Framework & Core Technologies

### **Next.js**
- **Role**: Frontend framework  
- **Why**: Industry-standard for React-based apps, perfect for component reuse, routing, and performance  
- **Used for**: UI layout, routing, API integration, serverless edge functions (if needed)

### **Custom CSS**
- **Role**: Visual styling  
- **Why**: Allows full control over branding and layout from Figma designs  
- **Used for**: Reusable component styles, global theming, responsiveness

---

## 🎨 UI/UX Tools

### **Figma** (Design + FigJam)
- **Why**: All-in-one space for mockups, prototyping, and design documentation  
- **Used for**:
  - High-fidelity mockups (desktop and mobile)
  - Exporting design tokens for CSS
  - Mapping user flows (in FigJam)

---

## 📡 Data & API Services

### **OpenF1 API**
- **Role**: Main data source for race info, driver stats, team results, etc.  
- **Why**: Free, fast, and well-documented  
- **Used for**:
  - Live and historical F1 data
  - Enabling filters and views for users
  - Supporting AI-driven queries (via endpoint responses)

### **Mistral (Open-source LLM)**
- **Role**: Natural language processing  
- **Why**: Lightweight and open-source, great for converting user questions into structured API calls  
- **Used for**:
  - Processing user queries like "Who DNF’d in Baku?"
  - Determining which UI module to use (e.g. table, stat card)
  - Optional: Hosted via Together.ai, Groq, or Fireworks

---

## ☁️ Deployment & Infrastructure

### **Vercel**
- **Role**: Hosting and continuous deployment  
- **Why**: Seamless with Next.js and GitHub  
- **Used for**:
  - Automatic deploys from `main` branch
  - Live previews
  - Free hosting for static and dynamic content

### **GitHub**
- **Role**: Source control + project management  
- **Used for**:
  - Code hosting
  - GitHub Projects for roadmap and backlog
  - GitHub Issues for bugs, features, and todos

---

## ✅ Optional or Future Tools

| Tool                    | Use Case                          |
|-------------------------|-----------------------------------|
| Framer Motion           | Smooth animations and transitions |
| Storybook               | Visual component documentation    |
| Postman                 | API testing and exploration       |
| Vercel Analytics / Plausible | Track real usage             |

---

_Last updated: 2025-06-30_