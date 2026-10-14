# DaVinci Resolve Student Tutorial Prototype

Interactive browser-based teaching prototype created by Joe Nasr for DaVinci Resolve students.

The project was built as a vibe-coding experiment to explore how course material could be turned into a lightweight interactive web tutorial instead of a static handout or slide deck.

Live prototype:
https://joenasriani.github.io/davinci-tutorial/

## Teaching scope

The prototype organizes DaVinci Resolve material into a multi-part learning sequence covering:

- Media, Cut, Edit, Fusion, Color, Fairlight, and Deliver pages
- timeline navigation and editing workflow
- trimming tools
- keyframing
- titles and Text+
- compound clips
- Inspector controls
- scaling and positioning
- transitions
- Open FX
- generators
- export and delivery workflow
- final knowledge quiz

## Implementation

The prototype is built as a static front-end learning experience using:

- HTML
- CSS
- JavaScript
- Tailwind CSS via CDN
- Google Fonts
- local instructional images
- client-side navigation
- responsive layouts
- interactive quiz logic

The tutorial is divided into standalone HTML modules that link together as a sequential course. The root `index.html` displays Part 1 inside an iframe.

The project does not use a backend or application framework.

## Current limitations

- The tutorial demonstrates learning materials and quiz interactions in the browser; it is not a substitute for working inside DaVinci Resolve.
- Several source files (`davinci-gem-part4.html`, `davinci-gem-part5.html`, and `davinci-gem-part6.html`) use the same page title, "Delivering Your Project (Part 6)". The module naming and sequencing should be reviewed before treating them as seven distinct lessons.
- The final quiz is client-side; no learner accounts, server-side scoring, or accredited certification were identified in the inspected files.
- Pages load Tailwind CSS and Google Fonts from external services and may need network access for their intended styling.
- No application tests, production deployment audit, or DaVinci Resolve version compatibility test was run as part of this documentation update.

## Purpose

This repository documents an experiment in turning instructor-led DaVinci Resolve material into an interactive browser-based learning format for students.

Credit: Joe Nasr

Portfolio: https://joe-nasr-signals.vercel.app/
