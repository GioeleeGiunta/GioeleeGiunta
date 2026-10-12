  <p align="center"><h1>🌿 Code built by hand, the old-fashioned way.</h1>
</p>
<p align="center">
  <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExbGFydDY2OXp4eTlid3ZmdDFiemV1Mnc5ZGlseXBobGw3bjQyNmV1diZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZXBL0YtCVuC6liQBeF/giphy.gif" width="400" alt="Stay Amish"/>
</p>

<h1 align="center">Gioele Giunta</h1>

<p align="center">
  <b>Computer Engineering · Embedded Systems · Full Stack Development</b><br/>
  M.Sc. candidate in Embedded and Smart System Design · Politecnico di Torino
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/gioele-giunta-58314b203"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://gioelegiunta.it/"><img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=github&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=G103L3&label=Profile%20Views&color=0e75b6&style=for-the-badge"/>
</p>

---

## Featured Projects

### [exposingepstein.com](https://exposingepstein.com) · Epstein Investigation Archive *(proprietary, not on GitHub)*

A platform I built from scratch to make the DOJ Epstein files actually navigable. No company, no budget, no team. Just me and [AquaBomber](https://www.reddit.com/user/AquaBomber), who handled the community while I coded every day from morning until late into the night.

The platform now serves 100k+ daily users and holds:

- Over 180,000 photos from the DOJ seizure
- Over 2,000 videos, many with transcriptions and audio analysis
- Thousands of court documents, emails, and flight records, tagged and cross-referenced
- Full-text search across hundreds of thousands of PDFs
- User accounts, community posts, comments, voting, and collaborative investigations

The codebase is proprietary. The public API below is the open interface to the archive.

---

### [epstein-files-api](https://github.com/G103L3/epstein-files-api) · Public REST API for the Epstein Archive

A free, documented REST API built on top of exposingepstein.com so that researchers, journalists, and developers can access the archive programmatically without scraping anything.

- Paginated endpoints for documents, tags, and platform stats
- Full-text search across the archive
- API key registration in one request, 500 req/day free

```bash
curl -X POST "https://exposingepstein.com/backend/api/api_public.php?action=register" \
  -H "Content-Type: application/json" \
  -d '{"app_name": "my-tool", "email": "you@example.com"}'
```

---

### [AUSP-Protocol](https://github.com/G103L3/AUSP-Protocol) · Acoustic Underground Sensor Protocol

A layered acoustic communication protocol for master-slave sensor networks in underground environments (tunnels, mines, pipelines).  
Paper submitted to **IEEE Internet of Things Journal** (under review, 2026).

- 4-layer stack: Physical / Bit / Link / Application
- FFT-based tone detection at 48 kHz with parabolic peak interpolation
- Run-length encoding achieving up to 30 bps over acoustic channel
- Token-based MAC without clock synchronization
- Validated on ESP32 hardware at 14.4 bit/s average, less than 1% retransmission rate

```
G. Giunta, S. Monteleone, D. Patti,
"Acoustic Communication Protocol for Master-Slave Networks in Underground Environments,"
IEEE Internet of Things Journal, under review, 2026.
```

---

## About Me

I work at the intersection of embedded systems and software engineering. My background spans low-level firmware, protocol design, and full stack web and mobile development.

**Embedded Systems**
- Platforms: ESP32, STM32, Arduino Due, Tang Nano
- Focus on real-time signal processing, acoustic communication, and IoT

**Full Stack Development**
- React, React Native, PHP, PostgreSQL
- Built and scaled production platforms to 100k+ daily users

**Previous Role**
- Full Stack Developer at OTO Travel Technology

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=G103L3&show_icons=true&theme=radical" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=G103L3&layout=compact&theme=radical" height="160"/>
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=G103L3&theme=radical"/>
</p>

---

## Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=G103L3&theme=radical&no-bg=true&margin-w=10&row=2&column=4"/>
</p>

---

## Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/ESP32-black?style=for-the-badge&logo=espressif&logoColor=white"/>
  <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white"/>
</p>
