# NativeYoutube

A web application that enables users to input a YouTube video URL and receive a dubbed version in their native language using AI technologies.

## Overview

NativeYoutube leverages cutting-edge AI technologies to make YouTube content accessible across language barriers:

- Transcription with OpenAI Whisper
- Translation with GPT-4
- Voice generation with ElevenLabs
- Asynchronous processing with status tracking

## Features

- Simple YouTube URL submission
- Processing status tracking
- High-quality dubbed video playback
- Downloadable audio in MP3 format
- Dashboard for managing processed videos

## Technology Stack

- Frontend: Next.js 14, React 18, Tailwind CSS, DaisyUI
- Backend: Node.js 20+, Express.js, Bull+Redis for queues
- Database: SQLite (MVP), PostgreSQL (Phase 2)
- External APIs: YouTube, OpenAI (Whisper & GPT-4), ElevenLabs

## Development Status

Currently in Phase 1 (Core MVP) with focus on completing the processing pipeline integration. The frontend foundation is complete with all key pages and UI components implemented.