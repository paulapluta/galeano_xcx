# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

A single-page poem display. Open `index.html` directly in a browser — no build step, server, or dependencies.

## Structure

- `index.html` — all HTML and CSS in one file; no JavaScript
- `letterpress.png` — poster image displayed in the left column (must stay alongside `index.html`)

## Design

Two-column layout: letterpress image on the left, two stacked poem sections (English / Spanish) on the right. Fonts loaded from Google Fonts: Bebas Neue for titles, Inter for body. The image is sized with `max-height: calc(100vh - 7rem)` so it is always fully visible without cropping.
