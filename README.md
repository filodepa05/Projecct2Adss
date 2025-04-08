# Projecct2Adss

1. git checkout -b feature-contact-form
#Creates and switches to a new branch for the contact form feature
2. echo "<h1>Contact Us</h1>" > contact.html
#Creates a new HTML file with a basic heading.
3. git add contact.html
#Moves the file to the staging area to prepare it for commit.
4. git commit -m "Add basic contact page with heading"
#Saves the staged file to your local Git history.
5. git checkout main
Returns to the main branch of the repository.
6. git merge feature-contact-form
Combines the contact form work into the main branch.
7. git pull origin main --rebase
git push origin main
Ensures your local main is up to date, then uploads changes to GitHub.
