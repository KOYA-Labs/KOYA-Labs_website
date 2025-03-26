# KOYA Labs Website

Welcome to the **KOYA-Labs_website** repository! This repository hosts the source code and assets for the KOYA labs landing page, served at [www.koyalabs.ai](https://www.koyalabs.ai).

## Repository Structure

### `images/koya-logo.svg`
- **KOYA labs logo** used on the landing page. 
- Uses the svg file for for less data storage.

### `CNAME`
- Specifies the custom domain for GitHub Pages so that the site is accessible at https://www.koyalabs.ai.

### `fd88876636b744d045b0b81312adec80.html`
- Contains token for **Twilio domain ownership verification** (non-sensitive).

### `index.html`
- The **main landing page** for KOYA labs.
- Built with **Tailwind CSS**, configured to use the [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono) font. 
- Complies with **WCAG AAA standards** for color contrast.
- Contains the logo, mission and vision statements, and stealth-mode text.

---

## Working With This Repository

Below are instructions for cloning the repository, making changes, and pushing updates.

1. **Clone the repository (ONLY NEEDS TO BE PERFORMED ONCE)**

   ```bash
   git clone https://github.com/KOYA-Labs/KOYA-Labs_website.git

### OPTION A (simpler): Work directly on main branch

**Note: Working directly on the main branch is acceptable for small updates or personal projects. For collaborative projects or significant changes, it is recommended to use feature branches and pull requests (see OPTION B below) to ensure proper review and avoid unintentional disruptions to the live site.**

If you prefer to work directly on the main branch, follow these steps:

1. **Ensure you’re on the main branch**

   ```bash
   git checkout main

2. **Pull the latest changes from the main branch of the remote repository**

   ```bash
   git pull origin main

3. **Make your edits**

Edit the files directly on the main branch as needed in your code editor:
- Update index.html as needed.
- Add or modify files in the images folder if you have new assets.
- If you need to change the domain, update CNAME.
- For Twilio verification, ensure the verification file is correct.

4. **Stage and Commit your changes**

   ```bash
   git add .
   git commit -m "Describe the changes you made"

5. **Push your changes to GitHub**

   ```bash
   git push origin main

### OPTION B: Work on feature branches

1. **Ensure you’re on the main branch**

   ```bash
   git checkout main

2. **Pull the latest changes from the main branch of the remote repository**

   ```bash
   git pull origin main

3. **Create a new branch to implement changes**

   ```bash
   git checkout -b my-feature-branch

(Optionally replace my-feature-branch with a descriptive name for your changes.)

4. **Make your edits**

Edit the files directly on the main branch as needed in your code editor:
- Update index.html as needed.
- Add or modify files in the images folder if you have new assets.
- If you need to change the domain, update CNAME.
- For Twilio verification, ensure the verification file is correct.

5. **Stage and Commit your changes**

   ```bash
   git add .
   git commit -m "Describe your changes here"

6. **Push your changes to GitHub**

   ```bash
   git push origin my-feature-branch

7. **Open a Pull Request (PR)**

- Go to the GitHub page of your repository fork.
- Click "Compare & Pull request".
- (Optionally provide a clear description of what your changes do.)
- Open the PR.

8. **Merge the Pull Request**

Once reviewed and approved, merge the PR into the main branch.
Your changes will be published to https://www.koyalabs.ai shortly thereafter (GitHub Pages automatically rebuilds).

9. **Clean up**

Switch back to main locally, pull the latest changes into main, and optionally delete the feature branch (via the terminal in your code editor and/or directly on GitHub).

   ```bash
   git checkout main
   git pull origin main
   git branch -d my-feature-branch
