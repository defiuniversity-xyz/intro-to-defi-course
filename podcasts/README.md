# Intro to DeFi - Podcasts

This folder contains 12 podcast files (`.m4a`) for upload to Google Cloud Storage. The upload script (`tools/upload_media.py`) reads from here directly—no moving or renaming required.

**File format:** `lessonN Title_With_Underscores.m4a` (e.g., `lesson1 Replacing_Bankers_With_Code.m4a`). The script extracts the lesson number and uploads to GCS at `lesson-NN/audio/`.
