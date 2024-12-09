# Project Workflow Documentation

This document provides a detailed record of the tasks completed for both Jamie and Morgan in the development of this web project.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Tasks Completed for Jamie](#tasks-completed-for-jamie)
3. [Tasks Completed for Morgan](#tasks-completed-for-morgan)
4. [Additional Notes](#additional-notes)

---

## Project Overview

This project involves collaborative development to create and enhance a basic web project which I acted as 2 users (morgan and Jamie to carry out tasks)
- **Jamie’s Task**: Create the foundational pages and update the `main` branch. 
- **Morgan’s Task**: Add a new `book_reviews.html` page in a feature branch and prepare it for integration with the main branch.

---

## Tasks Completed for Jamie

The following tasks were completed on behalf of Jamie:

1. **Updated the `main` branch**  
   - Verified that the current branch was set to `main`.  

2. **Created foundational HTML files**  
   - Added the following files to the repository:
     - `home.html`
     - `about_us.html`
     - `events.html`
     - `contact_us.html`

3. **Added sample content to each file**  
   - Each file was populated with basic HTML content.  
     Example for `index.html`:
     ```html
     <h>Greenwood does so many things</h1>
     ```

4. **Staged and committed changes**  
   - All files were staged and committed with the message:  
     ```bash
     git commit -m "update changes"
     ```

5. **Pushed changes to the remote repository**  
   - Pushed the updates directly to the `main` branch:
     ```bash
     git push origin main
     ```

---

## Tasks Completed for Morgan

The following tasks were completed on behalf of Morgan:

1. **Created a feature branch**  
   - A new branch named `add-book-reviews` was created:
     ```bash
     git checkout -b add-book-reviews
     ```

2. **Added the `book_reviews.html` file**  
   - Created a new file named `book_reviews.html` in the project directory.

3. **Added sample content to the file**  
   - Populated the file with basic HTML content:
     ```html
     <!DOCTYPE html>
     <html lang="en">
     <head>
         <title>Book Reviews</title>
     </head>
     <body>
         <h1>Book Reviews Section</h1>
         <p>This page contains book reviews.</p>
     </body>
     </html>
     ```

4. **Staged and committed changes**  
   - Staged the file and committed it with the message:
     ```bash
     git commit -m "Add book reviews section"
     ```

5. **Pushed the feature branch to the remote repository**  
   - Pushed the branch to the remote repository:
     ```bash
     git push origin add-book-reviews
     ```

6. **Created a Pull Request**  
   - A Pull Request (PR) was raised to merge the `add-book-reviews` branch into the `main` branch:
     - Title: "Add book reviews section to the website"
     - Description: Detailed the changes made to the `book_reviews.html` file.

---

## Additional Notes

- Ensure all changes have been tested locally before pushing them to the repository.
- Use clear and descriptive commit messages for better collaboration and version control.
- Any updates to the `main` branch should go through code review if working in a team.

---
