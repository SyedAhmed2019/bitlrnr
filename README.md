# BitLrnr

Learning portal for 15-minute courses (Python, Go, Java, Rust) with inline code tryout, quizzes, tiers, and community Q&A.

- **Repo:** https://github.com/SyedAhmed2019/bitlrnr
- **Progress tracker:** [Google Sheet](https://docs.google.com/spreadsheets/d/1NlJI9oz3bfAtnEgEAc1h81Xwmo5Es5obYOh2arTP6b0/edit)
- **Daily plan CSVs:** `docs/tracking/`

## Layout

```
bitlrnr/
├── portal/          # Next.js web app (coming Day 2)
├── courses/         # Lesson content (markdown, code, quizzes)
├── docker/          # Compose fragments / configs
├── docs/            # Plans, tracking, schemas
└── docker-compose.yml
```

## Quick start (after Day 2)

```bash
cd portal && npm install && npm run dev
docker compose up -d
```
