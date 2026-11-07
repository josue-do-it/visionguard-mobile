# VisionGuard AI — Mobile Tracker

Installable mobile PWA for tracking an end-to-end YOLO audit on BDD100K.

## Features
- 10 project modules and completion progress
- Weekly objective and experiment notebook
- JSON export
- Offline shell cache and Android installation support
- Local browser storage (no cloud synchronization)

## Deploy
GitHub Actions workflow in `.github/workflows/pages.yml` publishes the repository root to GitHub Pages.

In GitHub: **Settings → Pages → Build and deployment → Source → GitHub Actions**.

Expected URL: https://josue-do-it.github.io/visionguard-mobile/

## Research integrity
Split by video sequence/scene; never use the test set for model selection; manually verify suspected annotation errors; preserve configs, seeds and versions; never invent results.

## Privacy
Progress and notes remain in this browser's localStorage. Export JSON regularly to keep a backup. Clearing browser data can erase local progress.