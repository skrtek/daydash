# daydash
DayDash is a one-page daily dashboard that runs locally in the browser. It provides quick access to notes, tasks, appointments, health info, weather, news headlines, and your favorite links—everything you need for your day, in one clean, responsive, modern interface.

Features
Header with greeting and current date (e.g. “Hello — Tuesday, October 28, 2025”)
Notes: multiline textarea to write daily thoughts
To-Do List: add tasks, mark as done, remove tasks
Appointments: schedule events with date + time, view upcoming, delete
Health Tracker: placeholders for COVID-19, Influenza, RSV positivity percentages + health notes
Weather: current weather + short hourly forecast (via Open-Meteo API)
News: top 5 headlines (via news API like GNews)
Favorites: categorize your quick links, add/delete links & categories, collapse/expand categories
Light / Dark mode toggle
Responsive layout: mobile-friendly (single-column) and desktop layout (two columns)
Clean, modern design with card components, accent colors, system/Apple-style fonts
Persistent storage using localStorage so your data stays in your browser
Tech Stack & Dependencies
Pure HTML, CSS, and JavaScript — no external frameworks required
Open-Meteo (or similar) for weather data (replace latitude & longitude)
News API (e.g., GNews) for fetching top headlines
Placeholder for Health data — you can integrate with Public Health Ontario or any API that provides respiratory virus positivity rates
