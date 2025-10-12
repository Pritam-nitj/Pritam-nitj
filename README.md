<!--
README.md for Pritam
Data used from the uploaded resume. :contentReference[oaicite:1]{index=1}
-->

<!-- Animated header SVG -->
<div align="center">
  <svg width="100%" viewBox="0 0 1000 180" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid meet">
    <defs>
      <linearGradient id="g1" x1="0%" x2="100%">
        <stop offset="0%" stop-color="#06b6d4"/>
        <stop offset="50%" stop-color="#7c3aed"/>
        <stop offset="100%" stop-color="#06b6d4"/>
      </linearGradient>
      <filter id="f1" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="6" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <!-- Background rounded card -->
    <rect x="10" y="10" rx="14" ry="14" width="980" height="160" fill="white" opacity="0.03"/>

    <!-- Name text with animated gradient stroke -->
    <text x="50%" y="55" font-family="Segoe UI, Roboto, Helvetica, Arial, sans-serif"
          font-weight="700" font-size="42" text-anchor="middle" fill="url(#g1)" >
      Pritam
      <animate attributeName="x" from="50%" to="50%" dur="1s" begin="0s" fill="freeze"/>
    </text>

    <!-- Subtitle -->
    <text x="50%" y="95" font-family="Segoe UI, Roboto, Helvetica, Arial, sans-serif"
          font-size="18" text-anchor="middle" fill="#9ca3af">
      Full-stack Developer • MERN & Next.js • TypeScript & PostgreSQL
    </text>

    <!-- Rotating gear mark -->
    <g transform="translate(920,40)">
      <g>
        <circle cx="0" cy="0" r="26" fill="none" stroke="url(#g1)" stroke-width="3"/>
        <g transform="scale(0.65)">
          <path d="M6 -12 L 12 -6 L 6 0 L -6 0 L -12 -6 L -6 -12 Z" fill="url(#g1)"/>
        </g>
        <animateTransform attributeName="transform"
                          type="rotate"
                          from="0 0 0"
                          to="360 0 0"
                          dur="6s"
                          repeatCount="indefinite"/>
      </g>
    </g>
  </svg>
</div>

---

<!-- About -->
### About
I am a Full-stack developer (B.Tech Information Technology) building production-quality web applications using modern stacks such as Next.js, Node.js, React, PostgreSQL and MongoDB. I design scalable backend schemas and focus on clean UX in the frontend. Data below is taken from my resume. :contentReference[oaicite:2]{index=2}

---

### Education
- **B.Tech in Information Technology** — Dr. B.R. Ambedkar National Institute of Technology, Jalandhar. (CGPA: 7.20) :contentReference[oaicite:3]{index=3}
- **Intermediate** — Police D.A.V Public School, Amritsar (94.6%). :contentReference[oaicite:4]{index=4}

---

### Projects
> Links below were listed in the resume. :contentReference[oaicite:5]{index=5}

#### Smart LMS — `Next.js • Prisma • PostgreSQL • TypeScript`  
🔗 https://github.com/Pritam-nitj/Smart-Library-MS  
- Smart, responsive Library Management System with server-side rendering.  
- Quick Issue/Return via QR code scanning to automate issuing and returning.  
- Fine payments via PhonePe, advanced book search & librarian/student dashboards. :contentReference[oaicite:6]{index=6}

#### Chat App — `MERN • Socket.io • TailwindCSS • DaisyUI • Zustand • JWT`  
🔗 https://github.com/Pritam-nitj/ChatApp  
- Real-time messaging with Socket.io, JWT authentication, online presence indicators.  
- Global state management via Zustand and modern styling with Tailwind + DaisyUI. :contentReference[oaicite:7]{index=7}

#### E-commerce WebApp — `React • Redux Toolkit • Node.js • Express • MongoDB`  
🔗 https://github.com/Pritam-nitj/mern-ecommerce  
- Full-stack e-commerce platform with admin panel, Cloudinary image uploads, PayPal integration. :contentReference[oaicite:8]{index=8}

#### Video Summarization Tool — `React • Python • OpenAI Whisper • BART`  
- Generates concise multilingual summaries and full transcriptions for video URLs; supports mind-map generation from summaries. :contentReference[oaicite:9]{index=9}

---

### Technical Skills
<!-- Skill badges as inline SVG chips -->
<div>
  <svg height="28">
    <rect rx="6" ry="6" width="120" height="28" fill="#111827"/>
    <text x="12" y="19" fill="#fff" font-size="12" font-family="Segoe UI, Roboto">JavaScript</text>
  </svg>
  <svg height="28">
    <rect rx="6" ry="6" width="90" height="28" fill="#111827"/>
    <text x="12" y="19" fill="#fff" font-size="12">TypeScript</text>
  </svg>
  <svg height="28">
    <rect rx="6" ry="6" width="120" height="28" fill="#111827"/>
    <text x="12" y="19" fill="#fff" font-size="12">React • Next.js</text>
  </svg>
  <svg height="28">
    <rect rx="6" ry="6" width="120" height="28" fill="#111827"/>
    <text x="12" y="19" fill="#fff" font-size="12">Node • Express</text>
  </svg>
  <svg height="28">
    <rect rx="6" ry="6" width="110" height="28" fill="#111827"/>
    <text x="12" y="19" fill="#fff" font-size="12">MongoDB • PostgreSQL</text>
  </svg>
  <svg height="28">
    <rect rx="6" ry="6" width="110" height="28" fill="#111827"/>
    <text x="12" y="19" fill="#fff" font-size="12">Prisma • Mongoose</text>
  </svg>
</div>

Technical skills summarized from resume. :contentReference[oaicite:10]{index=10}

---

### How I work
- Prefer clear API contracts, normalized DB schemas, and modular components.
- Focus on performance optimizations and accessible, responsive UI.
- Use Git & feature-branch workflow; deploy CI/CD for production builds.

---

### Quick contact
- Phone: `+91 6284986514`  
- Email: `pritamk6284987295@gmail.com`  
- LinkedIn: https://www.linkedin.com/in/Pritam-nitj/ :contentReference[oaicite:11]{index=11}  
- GitHub: https://github.com/Pritam-nitj :contentReference[oaicite:12]{index=12}

---

### Animated footer (subtle wave)
<svg viewBox="0 0 1200 80" width="100%" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <path id="wave" d="M0 40 C 150 80 350 0 600 40 C 850 80 1050 0 1200 40 L1200 100 L0 100 Z" fill="#0ea5a4" opacity="0.08">
    <animate attributeName="d" dur="8s" repeatCount="indefinite"
      values="
        M0 40 C 150 80 350 0 600 40 C 850 80 1050 0 1200 40 L1200 100 L0 100 Z;
        M0 40 C 150 0 350 80 600 40 C 850 0 1050 80 1200 40 L1200 100 L0 100 Z;
        M0 40 C 150 80 350 0 600 40 C 850 80 1050 0 1200 40 L1200 100 L0 100 Z" />
  </path>
</svg>

---

## Tips to customize
1. Replace header SVG text if you want a tagline change.  
2. Swap or add project links where needed — the README uses URLs pulled from your resume. :contentReference[oaicite:13]{index=13}  
3. If you want additional animated badges (GitHub stats, top languages), tell me which ones and I will generate them.

---

## Summary table

| Section | Source / Notes |
|---|---|
| Name & Contact | From resume (phone, email, LinkedIn, GitHub). :contentReference[oaicite:14]{index=14} |
| Education | B.Tech (NIT Jalandhar), Intermediate % included. :contentReference[oaicite:15]{index=15} |
| Key Projects | Smart LMS, Chat App, E-commerce, Video Summarization — descriptions & repo links from resume. :contentReference[oaicite:16]{index=16} |
| Tech & Tools | JS, TS, React, Next.js, Node, Express, MongoDB, PostgreSQL, Prisma, Tailwind, Zustand, Socket.io. :contentReference[oaicite:17]{index=17} |
| What I added | Inline SVG header, animated gear, skill chips, wave footer, and SMIL animations (works on GitHub). |

---

If you want, I can:
- produce a second variant with dark-themed SVGs and icons, or
- output the same README as a ready file to download, or
- add GitHub dynamic widgets (language stats / streak) — tell me which and I'll include them.

