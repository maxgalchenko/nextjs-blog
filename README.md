# Next.js Static Blog

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-9.3.5-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-16.13.1-blue?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-18.17.0-green?style=for-the-badge&logo=node.js)

</div>

## Overview

A markdown-based blog built with Next.js demonstrating Static Site Generation (SSG) and file-based routing. Created as a learning project to explore Next.js fundamentals, markdown parsing, and pre-rendering strategies.

## Key Features

- Static Site Generation with markdown files
- Automatic route generation from file system
- Markdown parsing with gray-matter frontmatter support
- Date formatting with date-fns
- Dynamic routing with `getStaticPaths` and `getStaticProps`

## Tech Stack

React 16, Next.js 9 (Pages Router), date-fns, gray-matter, remark

## Architecture

Classic Next.js Pages Router architecture with file-based routing. Markdown posts stored in `/posts` directory are parsed at build time using gray-matter for frontmatter and remark for HTML conversion. Static pages generated via `getStaticProps` and `getStaticPaths` for optimal performance.

## Prerequisites

- Node.js: `16.x`

## Installation

```bash
git clone https://github.com/maxgalchenko/nextjs-blog.git
cd nextjs-blog
npm install
```

## Quick Start

```bash
npm run dev
# Open http://localhost:3000

# Production
npm run build
npm start
```

## Available Scripts

- `npm run dev` – Start development server on port 3000
- `npm run build` – Create optimized production build
- `npm start` – Start production server

## Screenshots

![Blog Homepage](<./public/localhost_3000_%20(5).png>)

![Blog Post](<./public/localhost_3000_%20(6).png>)

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
