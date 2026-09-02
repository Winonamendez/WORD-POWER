WORD POWER! VERSION 5 — TEACHER UPDATES
========================================

UPLOAD/REPLACE THESE FILES IN THE ROOT OF YOUR EXISTING WORD-POWER GITHUB REPOSITORY:
- index.html
- manifest.json
- service-worker.js
- icon.svg
- teacher-updates.json

Version 5 adds a shared Teacher Updates feed while keeping each family's progress local to their own device.

IMPORTANT: Keep the SAME GitHub repository and Pages URL. Do not create a new Pages site.

HOW TO ADD A FUTURE TEACHER LIST
1. Edit teacher-updates.json on GitHub.
2. Add a lesson with a permanent unique id, updateVersion 1, type hfw or spelling, testDate, words, and optional story.
3. Commit the file.
4. Families tap Check Teacher Updates in the app.

HOW TO CORRECT AN EXISTING SHARED LESSON
- Keep the exact same id.
- Increase updateVersion (for example 1 to 2).
- Make the corrections and commit.
- The app will show UPDATE instead of creating a duplicate.

PROGRESS
- Stars, mastered words, Smart Review misses, and Story completion remain on each user's device.
- Updating a teacher lesson preserves matching progress for words that remain in the lesson.
- Version 4 browser data is migrated into Version 5 on the same GitHub Pages site.

DEFAULT PARENT PIN: 1234
