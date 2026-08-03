# C Programming Labs

![C](https://img.shields.io/badge/language-C-blue)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

A collection of small C console applications built as part of my university coursework, consolidated into a single repository. Each subfolder is a self-contained project demonstrating core C concepts: structs, arrays, pointers, file I/O, and CSV persistence.

## Projects

| Project | Description |
|---|---|
| [course-csv-manager](course-csv-manager) | Course registration system with CSV persistence — add, search, update, delete |
| [theme-park-ticketing](theme-park-ticketing) | Menu-driven ticketing system with pricing, bulk discounts, and meal add-ons |
| [playlist-organizer](playlist-organizer) | Playlist manager — display, sort (selection & bubble sort), and delete songs |
| [calories-goal-tracker](calories-goal-tracker) | Logs steps, calories, and distance; tracks progress toward a daily goal |
| [study-hours-tracker](study-hours-tracker) | Tracks and compares study hours across subjects over two weeks |
| [temperature-tracker](temperature-tracker) | Records daily temperatures and computes statistics using pointers and arrays |

Each project folder has its own README with build/run instructions and (where available) example output.

## Build

Each project is a standalone C program. From inside a project's `src/` folder:

```bash
gcc *.c -o app
./app
```

## License

MIT — see [LICENSE](LICENSE).
