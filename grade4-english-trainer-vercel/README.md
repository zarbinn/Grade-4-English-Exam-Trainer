# Grade 4 English Exam Trainer — Subcategory Edition

A mobile-friendly, static English grammar learning app that can be hosted on Vercel.

## Structure

- **13 main grammar topics**, split into **48 independent subcategories**.
- Every subcategory has a simple Grade 4 explanation and **one worked example with its answer**.
- Every subcategory has **10 separate, scored questions**, worth 10 marks. The worked example is never scored or reused as a question.
- **480 scored questions in the full exam**, worth **480 marks**.
- Practice a single subcategory (10 marks), a whole main topic (20–50 marks), or the complete exam (480 marks).
- Multiple-choice and short typed-answer questions with immediate correct/incorrect feedback, the correct answer and an explanation.
- End-of-test results include marks for each subcategory, main topic and the overall percentage.
- Retry incorrect answers, review the answer key and view recent results on the same device.

## Deploy to Vercel

1. Extract the ZIP file.
2. Upload `index.html`, `app.js`, `styles.css`, `questions.json`, and `README.md` to the **root** of a new GitHub repository.
3. Open https://vercel.com and choose **Add New → Project**.
4. Import the repository and select **Framework Preset: Other**.
5. Leave the build command empty. Set the output directory to `.` (the project root) and deploy.

No database, build process or environment variables are needed. You can also test it locally with `python3 -m http.server 8000` and visit http://localhost:8000.

## Notes

Results are saved in the browser's local storage, not synced across devices. Typed answers are checked against the expected answer, ignoring case, surrounding whitespace and optional sentence-ending punctuation. Other acceptable creative answers are not automatically assessed. The questions and lesson explanations can be edited in `questions.json`.
