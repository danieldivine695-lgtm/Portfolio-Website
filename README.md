# 🚀 AI Automation Architect Portfolio

A production-grade personal portfolio built with Next.js 14+, TypeScript, and Tailwind CSS. Designed for high-performance, accessibility, and strict legal compliance.

## 🛠️ Tech Stack
- **Framework:** Next.js 14 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Animations:** Framer Motion
- **Icons:** Lucide React
- **Validation:** Zod
- **Forms:** React Hook Form
- **Testing:** Vitest & Playwright

## 📁 Architecture
- `src/app`: App Router pages and API routes.
- `src/components`: Atomic UI components.
- `src/lib`: Shared utilities (metadata construction, project fetching).
- `src/types`: TypeScript interfaces for content.
- `src/content`: Local JSON/MDX "CMS" for projects and blog posts.

## 🚀 Getting Started

### Installation
\`\`\`bash
npm install
\`\`\`

### Development
\`\`\`bash
npm run dev
\`\`\`

### Production Build
\`\`\`bash
npm run build
\`\`\`

### Testing
- **Unit Tests:** \`npm test\`
- **E2E Tests:** \`npm run test:e2e\`

## 📈 Adding Content
To add a new project:
1. Open `src/content/projects.json`.
2. Add a new object following the `Project` interface.
3. The site will automatically generate a new detail page at \`/projects/[slug]\`.

## ⚖️ Compliance & Data Minimization
This site is built with a "Privacy by Design" approach:
- **Data Minimization:** The contact form only collects Name, Email, and Message. No unnecessary fields are requested.
- **Explicit Consent:** An unchecked-by-default consent box is required before submission.
- **No Tracking:** No third-party analytics or tracking pixels are installed.
- **Local Preferences:** Theme preferences are stored in \`localStorage\`, not cookies.

## 🛠️ Third-Party Embeds
- **Fonts:** Google Fonts (loaded via `next/font` to prevent layout shift and external requests).
- **Icons:** Lucide React (bundled locally).

## 📋 Human Review Checklist (Pre-Launch)
- [ ] **Legal Review:** Verify the Privacy Policy and Terms match your specific jurisdiction.
- [ ] **Business Details:** Update the contact email and business identity placeholders.
- [ ] **Real Images:** Replace the `[Project Image]` placeholders with actual screenshots.
- [ ] **Licensing:** Ensure all images used are properly licensed.
- [ ] **Links:** Verify all external project and social links are correct.
