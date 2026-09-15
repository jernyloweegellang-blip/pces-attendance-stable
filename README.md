# PCES Attendance with Bulk Registration and QR

## Start
1. Drag all project files into a blank Vite project.
2. Run `npm install`.
3. Run `npm run dev`.

## Bulk registration
Open Learners, download the CSV template, complete it in Excel, save as CSV UTF-8, then upload it.
Required headers: learner_id,name,grade,section. Optional: guardian,contact,email.

## Bulk QR
Filter grade and section, then choose Print/Save All Filtered QR IDs or Bulk Download QR ZIP.

This stable version uses browser LocalStorage and does not require Firebase or .env.
