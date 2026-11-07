# 🌐 Google Sites Portfolio Setup Blueprint
**Candidate:** David Ng Kah Xian | Site Reliability Engineer (SRE)

---

## 🚀 Quick Start: Creating the Site on Google Sites

1. Open your browser and go to **[sites.google.com](https://sites.google.com/)**.
2. Click **Blank** (or choose the **Portfolio** template).
3. Set your site document title (top-left corner): `David Ng - Portfolio`.

---

## 🎨 Recommended Styling & Themes

In the right-hand panel, click the **Themes** tab:
- **Theme:** Select **"Aristotle"** or **"Vision"**.
- **Color Accent:** Deep Navy/Blue (`#1e40af` or `#2563eb`) or Dark Slate.
- **Font Style:** Modern or Classic.

---

## 📐 Page Structure & Content

You can build this as a **Single-Page Scrolling Portfolio** (recommended for recruiters) or a **Multi-Page Site** (Home, Projects, Experience, Contact).

---

### Section 1: Header / Hero Banner
- **Header Type:** Banner or Large Banner.
- **Site Name:** `David Ng Kah Xian`
- **Banner Title:**
  ```text
  David Ng Kah Xian
  Site Reliability Engineer | Cloud Infrastructure & AI Automation
  ```
- **Insert a Button below the title:**
  - Name: `Get In Touch` | Link: `mailto:davidng7988@gmail.com`
  - Name: `GitHub Profile` | Link: `https://github.com/david894`

---

### Section 2: Professional Profile (About Me)
- **Insert:** Text Box (Set style to **Emphasis 1** or **Emphasis 2** for background contrast).
- **Heading:** `About Me`
- **Body Text:**
  ```text
  I am a forward-thinking Site Reliability Engineer specializing in high-availability (HA) banking operations, resilient backend microservices, and enterprise cloud maintenance. Proven track record in managing Alibaba Cloud infrastructure, disaster recovery practices, and automated incident resolution. 

  I combine deep expertise in high-concurrency Java/Spring Boot systems with advanced AI tool integration (Model Context Protocol / MCP) to eliminate operational bottlenecks, optimize cloud reliability, and drive engineering efficiency at scale.
  ```

---

### Section 3: Technical Skills
- **Layout:** Insert **3-Column** or **4-Column** content blocks.

#### Column 1: SRE & Cloud Infrastructure
- **Header:** `🛡️ SRE & Cloud`
- **Bullets:**
  - Platform Engineering & High Availability (HA)
  - Alibaba Cloud ECS, AWS, GCP
  - Disaster Recovery & Security Patching
  - JVM & Database Production Diagnostics

#### Column 2: Backend & Distributed Systems
- **Header:** `⚙️ Backend & Messaging`
- **Bullets:**
  - Java & Spring Boot
  - Apache RocketMQ & Nacos
  - SQL Query Optimization & Advanced Indexing
  - Microservices Architecture & REST APIs

#### Column 3: AI & DevOps Automation
- **Header:** `🤖 AI & DevOps`
- **Bullets:**
  - Agentic Coding & Model Context Protocol (MCP)
  - Vertex AI (Gemini) Integration
  - CI/CD Pipeline Design & Automated Deployment
  - Git VCS, Python Automation Scripting

---

### Section 4: Work Experience
- **Layout:** Collapsible Group or Single Content Block.
- **Heading:** `Professional Experience`
- **Subheading:** `SRE Engineer | Ant International` *(DEC 2025 – PRESENT)*
- **Bullet Points:**
  - **High Availability & Cloud Maintenance:** Architected and maintained robust Alibaba Cloud infrastructure for banking operations, ensuring high availability (HA), executing regular security patching, and enforcing rigorous disaster recovery practices.
  - **Backend Platform & Data Validation:** Owned a high-concurrency data validation platform processing billions of transactions via RocketMQ, guaranteeing data integrity across distributed microservice databases.
  - **Database Optimization & Engineering:** Drove full-stack backend feature development and database optimizations (advanced indexing, query efficiency tuning, and scheduled archiving) while managing weekly CI/CD release cycles and JAR deployments.
  - **Reliability Automation & AI Integration:** Rapidly resolved production bottlenecks (Old GC, slow SQL) and developed custom AI agent skills using Model Context Protocol (MCP) to automate system diagnostics and incident troubleshooting.
  - **Team Leadership & Compliance:** Supported strict banking audit regulations, drafted technical onboarding guides, and mentored engineering interns to successfully meet their OKRs.

---

### Section 5: Featured Projects
- **Layout:** Insert a **2-Column Content Block** (`Layouts` section in the right sidebar).

#### Project 1: Real-Time Data Validation Platform
- **Sub-tag:** Banking Operations & Distributed Systems
- **Details:**
  - Engineered a high-concurrency microservice validation engine, integrating RocketMQ to process billions of transactional database events with zero data inconsistency.
  - Developed custom AI agent skills utilizing Model Context Protocol (MCP) to automate system diagnostics and incident root-cause analysis, significantly reducing manual troubleshooting time.
  - Optimized scalability via advanced database indexing and archiving, alongside designing high-availability network architectures on Alibaba Cloud ECS to ensure strict regulatory compliance.
- **Tech Stack:** `RocketMQ`, `Alibaba Cloud ECS`, `Model Context Protocol (MCP)`, `Java/Spring Boot`

#### Project 2: Really Reply - AI-Powered WhatsApp Customer Support
- **Sub-tag:** Serverless & Generative AI
- **Details:**
  - Built a multi-tenant, serverless WhatsApp AI assistant using Python and Google Cloud Functions. Integrated Meta API webhooks and Vertex AI (Gemini) for real-time, AI-powered conversations.
  - Automated document ingestion from Google Drive and enabled semantic knowledge-base search, reducing customer query response time by ~60%.
  - Designed for scalability with Cloud SQL + Pyvector, ensuring secure, enterprise-ready vector search deployment.
- **Tech Stack:** `Python`, `Google Cloud Functions`, `Vertex AI (Gemini)`, `Meta API`, `Cloud SQL + Pyvector`

---

### Section 6: Education & Languages
- **Layout:** 2-Column Content Block.
- **Left Column: Education**
  - **Degree:** Bachelor of Software Engineering (软件工程学士学位)
  - **Institution:** Tunku Abdul Rahman University of Management and Technology (TARUMT)
  - **Period:** 2021 – 2025
- **Right Column: Languages**
  - English (Fluent / 精通)
  - Chinese / Mandarin (Fluent / 精通)
  - Malay (Fluent / 精通)

---

### Section 7: Bilingual Support (English / 中文)
For Google Sites:
- You can create two top-level page groups: **EN** (English) and **中文** (Chinese), or use the interactive embed code provided in `index.html` which features an instantaneous one-click **[ EN | 中文 ]** switch and a **[ ☀️ / 🌙 ] Light/Dark mode** toggle!

---

### Section 7: Contact & Social Footer
- **Layout:** Centered Text Box or Embed Block.
- **Text:**
  - 📧 Email: [davidng7988@gmail.com](mailto:davidng7988@gmail.com)
  - 📞 Phone: [+601137921123](tel:+601137921123)
  - 🐙 GitHub: [github.com/david894](https://github.com/david894)
  - 💼 LinkedIn: David Ng Kah Xian
  - 📍 Location: Sentul, Kuala Lumpur, Malaysia

---

## 💡 Pro Tip: Custom Embed Widgets for Google Sites

Google Sites has an **`Embed` > `Embed Code`** feature where you can paste custom HTML/CSS to make your site look modern, sleek, and interactive.

### Widget 1: Interactive Skill Badges
In Google Sites, click **Insert** > **Embed** > **Embed code**, and paste:
```html
<div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif; display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; padding: 10px;">
  <span style="background: #e0f2fe; color: #0369a1; padding: 6px 12px; border-radius: 20px; font-weight: 600; font-size: 13px;">Alibaba Cloud ECS</span>
  <span style="background: #e0f2fe; color: #0369a1; padding: 6px 12px; border-radius: 20px; font-weight: 600; font-size: 13px;">High Availability (HA)</span>
  <span style="background: #ede9fe; color: #6d28d9; padding: 6px 12px; border-radius: 20px; font-weight: 600; font-size: 13px;">Apache RocketMQ</span>
  <span style="background: #ede9fe; color: #6d28d9; padding: 6px 12px; border-radius: 20px; font-weight: 600; font-size: 13px;">Java & Spring Boot</span>
  <span style="background: #dcfce7; color: #15803d; padding: 6px 12px; border-radius: 20px; font-weight: 600; font-size: 13px;">Model Context Protocol (MCP)</span>
  <span style="background: #dcfce7; color: #15803d; padding: 6px 12px; border-radius: 20px; font-weight: 600; font-size: 13px;">Vertex AI (Gemini)</span>
  <span style="background: #fef3c7; color: #b45309; padding: 6px 12px; border-radius: 20px; font-weight: 600; font-size: 13px;">Disaster Recovery</span>
  <span style="background: #fef3c7; color: #b45309; padding: 6px 12px; border-radius: 20px; font-weight: 600; font-size: 13px;">CI/CD & DevOps</span>
</div>
```

### Widget 2: Embed Whole Preview Portfolio
You can also preview your complete standalone portfolio website directly by opening `portfolio_preview.html` in your web browser!
