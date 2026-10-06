# Caregiver Daily Notes

A lightweight tool for caregivers to record, organize, and search daily care notes by recipient and date.

## Purpose

This repository is intended for a simple caregiver notes application that helps track daily observations, care activities, and important events for care recipients.

## What a daily note contains

A daily note typically includes:

- **Care recipient** — the person the note is about
- **Date** — the calendar day the note refers to
- **Content** — observations, activities, medications, or other care details
- **Optional tags / category** — for quick filtering (e.g. medication, mood, incident)

## How notes are searched

- Filter by **care recipient**
- Filter by **date range** (inclusive start and end dates)
- Combine recipient + date filters
- Results ordered newest-first

Date boundaries are inclusive and compared as calendar dates (no time-of-day shifts).

## Usage example

To find notes for a care recipient named *Alex* between 1–7 October:

1. Select **Alex** in the recipient filter.
2. Set the start date to `2026-10-01` and the end date to `2026-10-07`.
3. View the matching notes, ordered from newest to oldest.
4. Use **Reset** to clear all filters and start a new search.

## Planned Features

- Create and edit daily care notes
- Filter notes by care recipient
- Filter by date range
- Simple, accessible interface
- Local-first or lightweight storage

## Status

Repository cleaned and ready for a fresh implementation.
