# Notedrop
---
## Overview

Notedrop is a secure note-taking application designed with privacy at its core. All notes are end-to-end encrypted, ensuring that only you can access your data. Built-in AI features help you summarize, and enhance your notes without compromising security.

## What This Repository Contains

This repository contains the **frontend client** for the Notedrop app.

You can access the live application at:  
[https://notedrop.app](https://notedrop.app) 

> Note: Backend is stored in this [repository](https://github.com/skulix01/notedrop-backend)

## Features

- **End-to-End Encryption**: Your notes are encrypted on your device before being sent to the server. No one else—not even the service providers—can read them.
- **Privacy First**: Zero-knowledge architecture; we never see your data.
- **Built-in AI**: Smart summarization, tagging, using local ai models run on device so your data never leaves your device.
- **Cross-Platform Sync**: Seamlessly sync notes across devices while maintaining full encryption.
- **Rich Text Editing**: Markdown and LaTeX support.

## Tech Stack

- Frontend: Next.js
- Encryption: Web Crypto API,
- State Management: Zustand
- UI Library: Tailwindcss, ShadCn

## License

This project is licensed under the **GNU Affero General Public License v3.0** - see the [LICENSE](LICENSE) file for details.

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)](https://nextjs.org/)
