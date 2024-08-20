# YouTube Video Downloader Extension

This repository contains a YouTube video downloader extension, built using Node.js, Express.js, and other powerful tools like `ffmpeg-static` and `ytdl-core`. This tool allows users to download YouTube videos directly through a web interface.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)

## Introduction

The YouTube Video Downloader Extension is a simple and efficient tool for downloading YouTube videos in various formats. It uses `ytdl-core` to fetch video data and `ffmpeg-static` to handle video conversion, ensuring high-quality downloads. The server is built with Express.js, making it a lightweight and fast solution.

## Features

- **Download YouTube Videos**: Supports downloading videos in multiple formats.
- **Fast and Reliable**: Utilizes `ffmpeg-static` for efficient video processing.
- **Cross-Origin Resource Sharing**: Enabled through CORS support.
- **Secure and Clean Filenames**: Ensures downloaded files have safe and sanitized filenames.

## Tech Stack

- **Backend**: Node.js, Express.js
- **Video Processing**: `ffmpeg-static`, `ytdl-core`
- **Utilities**: `dotenv` for environment variable management, `sanitize-filename` for safe file names

- **Frontend**: Basic HTML, CSS, and JavaScript for the web interface
