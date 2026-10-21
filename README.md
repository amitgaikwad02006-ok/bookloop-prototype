# BookLoop — Book Exchange & Donation Management System

A responsive, interactive frontend prototype for the C++ OOPs mini project. It is designed to deploy easily to GitHub Pages.

## What works
- Search books by title, author, subject, or owner
- Filter by status and subject; sort by title or recently added
- Add new book listings
- Submit donation or exchange requests
- Mark requested books as Reserved to prevent duplicate requests in the same browser
- Approve or reject requests from the request desk
- Update book status to Donated or Exchanged on approval
- Save prototype data in browser `localStorage`, so it persists across refreshes on the same browser
- Responsive desktop and mobile layout

## Run locally
1. Extract this ZIP.
2. Open `index.html` in a browser, or use VS Code's Live Server extension.
3. Try adding a book and submitting a request.

No build tools or dependencies are needed.

## Deploy to GitHub Pages
1. Sign in to GitHub and create a **new public repository**, for example `bookloop-prototype`.
2. Keep the repository initialized empty, or create it with a README.
3. In the repository, choose **Add file → Upload files** and upload `index.html` from this folder (you may also upload this README).
4. Commit the files to the `main` branch.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, select **Deploy from a branch**.
7. Select branch `main` and folder `/(root)`, then click **Save**.
8. Wait for the Pages deployment to finish. The URL will be shown in Settings → Pages and usually looks like `https://YOUR-USERNAME.github.io/bookloop-prototype/`.
9. Open the URL and test adding a book, requesting it, approving/rejecting, refreshing the page, and checking that the demo data persists.

## Important limitations to explain honestly
- This is a front-end prototype. Data is saved in each browser's local storage, not a shared online database. A different visitor or browser will not see the same listings or requests.
- The demo request desk has no authentication. Do not enter real phone numbers or personal data.
- For a real multi-user system, add a backend and shared database (for example, Firebase or Supabase) and authentication.
- The C++ OOPs program remains a separate console implementation. GitHub Pages hosts the website prototype; it does not run the C++ console app.

## Demo path for presentation
1. Search for `DSA`.
2. Click **Request** on an available book.
3. Enter a demo name, select Donation or Exchange, and send the request.
4. Show that the book changes to **Reserved**.
5. In Request desk, click **Approve** or **Reject**.
6. Show the updated status and the stats.
7. Add a new book and refresh the page to demonstrate local persistence.
