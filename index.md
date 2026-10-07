---
layout: default
title: Home
nav_order: 1
---

<div class="hero-section">
  <div class="profile-card">
    <div class="profile-image-container">
      <img src="profile%20pic%202.jpg" alt="Gerard Gallen" class="profile-photo" />
    </div>
    <div class="profile-content">
      <p class="eyebrow">Technical Writing • Information Architecture • Documentation Strategy</p>
      <h1 class="profile-title">Gerard Gallen</h1>
      <p class="profile-subtitle">Senior Technical Writer & Documentation Strategist</p>
      <p class="profile-summary">
        My role is to turn complex technical information into documentation that people can actually use. Whether the audience is a customer, administrator, or developer, I focus on making information clear, accessible, and practical.
      </p>
      <div class="cta-group">
        <a href="#portfolio" class="btn btn-primary">View portfolio</a>
        <a href="contact.md" class="btn btn-secondary">Contact me</a>
        <a href="Gerard%20Gallen%20CV%202026.docx" class="btn btn-tertiary">Download CV</a>
      </div>
    </div>
  </div>
</div>

---

## Core Strengths

<div class="expertise-grid">
  <div class="expertise-card">
    <h3>Documentation Strategy</h3>
    <p>Roadmaps, governance, standards, and scalable documentation systems aligned to product and business goals.</p>
  </div>

  <div class="expertise-card">
    <h3>Information Architecture</h3>
    <p>Content structures, taxonomies, navigation, and user-centred design that make complex systems easier to understand.</p>
  </div>

  <div class="expertise-card">
    <h3>Technical Writing</h3>
    <p>User guides, release notes, help centre content, API docs, and developer-facing documentation for complex products.</p>
  </div>

  <div class="expertise-card">
    <h3>Structured Authoring</h3>
    <p>DITA, Markdown, XML, HTML, topic-based writing, single-sourcing, and scalable workflows for maintainable content.</p>
  </div>

  <div class="expertise-card">
    <h3>Documentation Quality</h3>
    <p>Review frameworks, editorial standards, defect reduction, and process improvements that increase content quality.</p>
  </div>

  <div class="expertise-card">
    <h3>AI-assisted Documentation</h3>
    <p>Modern workflows that combine AI efficiency with governance, accuracy, and editorial control.</p>
  </div>
</div>

---

<a id="portfolio"></a>
## Portfolio Highlights

- **[SITA](sita/)** — Travel and passenger information documentation, AI-enabled workflow support, and content governance
- **[Bard na nGleann](bard-na-ngleann/)** — Product help centre content, developer documentation, and onboarding flows at Google
- **[Sidero](sidero/)** — Structured authoring for network documentation and agile delivery
- **[Innovatia](cisco/)** — Legacy content migration, release documentation, and documentation quality improvement at Cisco

---

## Why Employers Choose this Profile

- 10+ years of experience translating complex technical information into clear, usable content
- Experience working across enterprise software, SaaS, and global operations
- Strong user-centred approach grounded in information design and accessibility
- Skilled in both delivery and governance: writing, structure, review, and process improvement
- Comfortable working with product, engineering, support, and stakeholders in fast-moving environments

---

## Open to Opportunities

I am available for senior technical writing, documentation strategy, information architecture, or content operations roles where good documentation is a business asset and not a side task.

**[Contact me](contact.md)**  •  **[Download CV](Gerard%20Gallen%20CV%202026.docx)**

<style>
  .hero-section {
    margin-bottom: 2rem;
    background: linear-gradient(135deg, rgba(18, 56, 94, 0.04), rgba(33, 150, 243, 0.06));
    border: 1px solid rgba(18, 56, 94, 0.08);
    border-radius: 12px;
    padding: 2rem;
  }

  .profile-card {
    display: grid;
    grid-template-columns: 220px 1fr;
    gap: 2rem;
    align-items: center;
  }

  .profile-image-container {
    width: 220px;
    height: 220px;
    border-radius: 14px;
    overflow: hidden;
    border: 3px solid rgba(33, 150, 243, 0.8);
    background: linear-gradient(135deg, #eef4fb, #dfeaf7);
    box-shadow: 0 18px 40px rgba(33, 150, 243, 0.12);
  }

  .profile-photo {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
    filter: grayscale(100%) contrast(1.08) brightness(0.96) saturate(0.7);
  }

  .profile-content {
    min-width: 0;
  }

  .eyebrow {
    margin: 0 0 0.5rem 0;
    font-size: 0.76rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: #1d5f93;
  }

  .profile-title {
    margin: 0;
    font-size: clamp(2rem, 4vw, 2.8rem);
    line-height: 1.1;
    color: #1a1a1a;
  }

  .profile-subtitle {
    margin: 0.4rem 0 0.9rem 0;
    font-size: 1.2rem;
    font-weight: 600;
    color: #1a5d98;
  }

  .profile-summary {
    margin: 0 0 1.3rem 0;
    font-size: 1rem;
    line-height: 1.7;
    color: #3f3f3f;
    max-width: 60ch;
  }

  .cta-group {
    display: flex;
    gap: 0.75rem;
    flex-wrap: wrap;
  }

  .btn {
    display: inline-block;
    padding: 0.7rem 1.2rem;
    border-radius: 6px;
    font-weight: 600;
    font-size: 0.95rem;
    transition: all 0.2s ease;
    text-decoration: none;
    border: 2px solid transparent;
  }

  .btn-primary {
    background: #1d5f93;
    color: white;
  }

  .btn-primary:hover {
    background: #164d7d;
    text-decoration: none;
  }

  .btn-secondary {
    background: white;
    color: #1d5f93;
    border-color: #1d5f93;
  }

  .btn-secondary:hover {
    background: #f4f9ff;
    text-decoration: none;
  }

  .btn-tertiary {
    background: transparent;
    color: #1d5f93;
    border-color: #1d5f93;
  }

  .btn-tertiary:hover {
    background: rgba(29, 95, 147, 0.06);
    text-decoration: none;
  }

  .expertise-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 1rem;
    margin: 1.5rem 0 2rem 0;
  }

  .expertise-card {
    background: #f8fafc;
    border: 1px solid #e5edf5;
    border-radius: 8px;
    padding: 1.2rem 1rem;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .expertise-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 10px 22px rgba(0,0,0,0.04);
  }

  .expertise-card h3 {
    margin: 0 0 0.6rem 0;
    color: #1d5f93;
    font-size: 1.05rem;
  }

  .expertise-card p {
    margin: 0;
    line-height: 1.6;
    color: #4a4a4a;
  }

  @media (max-width: 768px) {
    .profile-card {
      grid-template-columns: 1fr;
      gap: 1.2rem;
      text-align: center;
    }

    .profile-image-container {
      width: 180px;
      height: 180px;
      margin: 0 auto;
    }

    .cta-group {
      justify-content: center;
    }
  }
</style>
