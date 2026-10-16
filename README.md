# Bharath Raj · AI Engineering Portfolio

A lightweight, responsive, zero-build portfolio for **B.S. Bharath Raj**, highlighting deployed AI engineering projects, work experience, technical skills and profiles.

## Features

- Custom dark visual design, responsive layout, mobile navigation, keyboard-accessible controls
- Project gallery with AI agents, applied ML and product filters
- Live deployment + GitHub source links with code-only projects clearly identified
- Experience, education, skills, contact and resume page
- No tracking scripts, frameworks, runtime API keys or build dependencies

## Local development

Open `index.html` in a browser or run:

```bash
python -m http.server 8080
```

Navigate to `http://localhost:8080`.

## Deployment

This is a static site: in Render choose **Static Site**, connect this repository, set publish directory to `.` and build command to `echo ready`. This repository contains the `render.yaml` blueprint for reproducible configuration.

## Customize

Update `script.js` to edit projects and deployment URLs, `index.html` for profile details and page sections, and `styles.css` for the design. The included `resume.html` was supplied as a resume reference and retains its original contents. The website uses the LinkedIn and LeetCode URLs provided separately (rather than outdated links in the resume).

## External demos

Hosted third-party apps may sleep, require sign-in, or be unavailable without warning. No project claims are based solely on being linked here.