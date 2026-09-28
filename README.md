# Quest Log

A private assignment dashboard. This repository holds only the app code: a sign-in screen and the dashboard logic.

- Sign-in and data are handled by Firebase Authentication and Cloud Firestore.
- All personal content (assignments, links, reviews and progress) lives in Firestore. Only approved accounts can read it (see `firestore.rules`).
- Nothing personal is stored in this repository.
