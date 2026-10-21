# Cineview DB — Movie Database (Case Study)

A movie catalogue and database application: browse, search, and explore a poster-driven movie library through a single-page interface backed by a PHP/MySQL database.

## How it was built

- **Front-end** — a single-page app shell (`index.html`) using the Foundation CSS framework and Sammy.js client-side routing, with jQuery and Slick carousel for the browsing experience. Movie artwork lives in `img/` (posters, hero art, branding).
- **Back-end** — PHP with a MySQL database holding the movie catalogue. Each movie also had its own media upload folder on the server, written by the app's upload flow.
- **Design** — bold, poster-first browsing: big hero imagery, horizontal carousels, and a retro display type treatment (Press Start 2P / Permanent Marker accents over Montserrat).

## Status of this repo

This project ran on hosting that has since been retired. The front-end shell and the poster artwork survived and are published here as a **code case study**; the compiled JS/CSS bundles and the PHP back-end did not survive the move, so there is no live demo. The repo shows the app's structure, interface design, and data-driven approach; a full restoration is planned if the original project files resurface.

## Tech

- HTML, CSS (Foundation), JavaScript (Sammy.js, jQuery, Slick)
- PHP, MySQL (original back-end)
