<h1 align="center">Hi, I'm Furi Sherpa Lama</h1>

<p align="center">
  <b>Aspiring DevOps &amp; Cloud Engineer</b> · AWS Certified Solutions Architect – Associate<br />
  Based in Kathmandu, Nepal
</p>

<p align="center">
  <a href="https://furi.info.np"><img src="https://img.shields.io/badge/Portfolio-furi.info.np-0f172a?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/lamafuri"><img src="https://img.shields.io/badge/LinkedIn-lamafuri-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:contact@furi.info.np"><img src="https://img.shields.io/badge/Email-contact%40furi.info.np-D14836?style=for-the-badge" alt="Email" /></a>
</p>

<p align="center">
  <img src="assets/terminal.svg" width="100%" alt="A terminal runs aws sts get-caller-identity and returns: Furi Sherpa Lama, Aspiring DevOps &amp; Cloud Engineer, AWS Certified Solutions Architect – Associate, Kathmandu, Nepal, open to work." />
</p>

---

## About me

I build and deploy full-stack JavaScript applications, from the database to the cloud server they run on.

```hcl
resource "cloud_engineer" "furi" {
  name          = "Furi Sherpa Lama"
  role          = "Aspiring DevOps & Cloud Engineer"
  location      = "Kathmandu, Nepal"
  certification = "AWS Certified Solutions Architect – Associate (SAA-C03, June 2026)"
  education     = "BSc (Hons) Computer Science with AI · Birmingham City University (Sunway College Kathmandu)"

  focus    = ["cloud", "devops", "backend"]
  learning = ["terraform", "kubernetes"]
  open_to  = ["full-time", "internships", "part-time / remote", "freelance"]

  highlights = [
    "Won 1st place in the DeerHack 2026 AI/ML track",
    "Built FlatShare, a MERN app used by 10 people in 2 shared flats for over 4 months",
  ]
}
```

---

## On AWS

<p align="center">
  <a href="https://www.credly.com/badges/99e06fd6-0ede-4ce8-8439-2aef47891cad/public_url"><img src="https://images.credly.com/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png" width="120" alt="AWS Certified Solutions Architect – Associate badge. Verify on Credly." /></a>
</p>

<p align="center">
  <b>AWS Certified Solutions Architect – Associate</b> · <a href="https://www.credly.com/badges/99e06fd6-0ede-4ce8-8439-2aef47891cad/public_url">verify on Credly</a>
</p>

<p align="center">
  <img src="assets/architecture.svg" width="100%" alt="AWS architecture: users reach Route 53, then an Application Load Balancer in a VPC that spreads traffic across an Auto Scaling group of EC2 instances in two Availability Zones running Nginx and Docker, backed by a Multi-AZ RDS PostgreSQL database, with S3, CloudWatch and IAM alongside." />
</p>

**How my apps ship**: every push to `main` is built and tested by GitHub Actions, packaged with Docker, and deployed to EC2 behind Nginx with SSL/TLS.

<p align="center">
  <img src="assets/pipeline.svg" width="100%" alt="Deploy pipeline: git push, GitHub Actions build and test, Docker image build, AWS EC2 with Nginx and SSL/TLS, live over HTTPS." />
</p>

---

## Tech stack

**Cloud & DevOps**

<p>
  <img src="https://skillicons.dev/icons?i=aws,docker,githubactions,nginx,linux,ubuntu,bash&perline=10" alt="AWS, Docker, GitHub Actions, Nginx, Linux, Ubuntu, Bash" />
</p>

AWS: EC2 · S3 · VPC · IAM · RDS · Elastic Load Balancing · Auto Scaling · CloudWatch · Route 53<br />
Also: Docker Compose · CI/CD · Nginx reverse proxy with SSL/TLS · cron jobs

**Backend**

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express&perline=10" alt="Node.js, Express" />
</p>

- **APIs:** REST API design with Node.js and Express · WebSockets
- **Auth:** JWT authentication with email OTP sign-up, and QR-code access for pharmacists (MedSync)
- **Background work:** 16 background jobs and cron scheduling (Kopila, FlatShare, MedSync)
- **Pipelines:** a 12-stage message-processing pipeline for Telegram messages and photos (Kopila)
- **Integrations:** a Python model service over REST, the Telegram Bot API, Google Gemini, and Cloudinary uploads
- **Data:** a 29-table PostgreSQL schema, and MongoDB with Mongoose
- **Testing:** 9 unit test suites that run without a database, network or API keys

**Databases**

<p>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,supabase,mysql&perline=10" alt="PostgreSQL, MongoDB, Supabase, MySQL" />
</p>

**Frontend**

<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,tailwind,html,css,figma&perline=10" alt="React, Next.js, TypeScript, JavaScript, Tailwind CSS, HTML, CSS, Figma" />
</p>

**Platforms & tools**

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vercel,netlify&perline=10" alt="Git, GitHub, Vercel, Netlify" />
  <img src="https://img.shields.io/badge/Render-000000?style=for-the-badge&logo=render&logoColor=white" alt="Render" height="48" />
</p>

**Currently learning**

<p>
  <img src="https://skillicons.dev/icons?i=terraform,kubernetes&perline=10" alt="Terraform, Kubernetes" />
</p>

---

## Featured projects

| Project | What it is | Built with |
| --- | --- | --- |
| **[Kopila](https://github.com/lamafuri/Kopila)** · [live](https://kopila.vercel.app) | An AI co-pilot for new parents that joins a family's Telegram group and builds the child's health record from ordinary messages. 29 database tables, 16 background jobs, a 12-stage message pipeline. *Technical Lead, Hackaverse 2026.* | Node.js, Express, PostgreSQL, React, Telegram Bot API, Google Gemini, Vercel, Render |
| **Drug-Drug Interaction Risk Analyzer** | Checks every drug pair in a prescription against 1,317 known side effects with a graph neural network. *1st place, DeerHack 2026 AI/ML track. Backend and Systems Lead.* | React, Node.js, Express, PostgreSQL, Python model service, REST APIs |
| **[FlatShare](https://github.com/lamafuri/Flat-Share)** · [live](https://flat-share-v1.vercel.app) | Expense sharing for shared flats: email OTP sign-up, group invites, Nepali (Bikram Sambat) dates and per-person bills. 10 active users for 4+ months. | React, Node.js, Express, MongoDB Atlas, JWT, Tailwind CSS |
| **AWS Cloud Deployment Lab** | A full-stack app on EC2, served over HTTPS with Nginx as reverse proxy, containerized with Docker and built by GitHub Actions. | AWS EC2, Nginx, SSL/TLS, Docker, GitHub Actions, Ubuntu |
| **[MedSync](https://github.com/lamafuri/MedSync)** · [live](https://med-sync-yukti.vercel.app) | QR-based medicine tracking: patient and pharmacist apps on one database, with a daily cron job for stock. | MongoDB, Express, React, Node.js, JWT, Cloudinary |
| **[Portfolio](https://furi.info.np)** | This portfolio: a scroll-driven climb from base camp to the summit, tailored to why you're visiting. | React, TypeScript, Vite, Tailwind CSS, GSAP, Framer Motion |

---

## Achievements

- 🥇 **1st Place, AI/ML Track** · DeerHack 2026 (June 2026)
- 🏅 **Shortlisted, LumbiniX 2026 National Hackathon** · one of 10 teams nationwide (Aug 2026)
- 🥈 **Runner-Up, CodeCraft C Programming Challenge** · National School of Sciences, 2024–25 (~150 participants)
- ☁️ **AWS Certified Solutions Architect – Associate** · Amazon Web Services (June 2026)

---

<p align="center">
  <a href="https://furi.info.np">furi.info.np</a>
</p>
