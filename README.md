# PCES Firebase Attendance Complete

## Included
Registration, edit, archive, restore, permanent delete, search, grade/section filters, individual QR download, grouped Print/Save All QR IDs, camera scanner, Firebase attendance, and CSV reports.

## Setup
1. Copy `.env.example` to `.env` and paste six Firebase Web App values.
2. Run `npm install` and `npm run dev`.
3. Enable Firebase Authentication Email/Password and create a user.
4. Create Firestore and publish `firestore.rules`.
5. For Vercel, add the same six environment variables and redeploy.

Deleting a learner does not delete old attendance documents.
