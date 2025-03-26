# KOYA Labs Website

Welcome to the **KOYA-Labs_website** repository! This repository hosts the source code and assets for the KOYA labs landing page, served at [www.koyalabs.ai](https://www.koyalabs.ai).

## Repository Structure

KOYA-Labs_website/ │ ├── images/ │ └── koya-logo.svg │ ├── CNAME │ └── (Contains the custom domain for GitHub Pages: "www.koyalabs.ai") │ ├── fd88876636b744d045b0b81312adec80.html │ └── (Twilio domain verification file) │ └── index.html └── (Main HTML file for the KOYA labs landing page)


### `images/koya-logo.svg`
- **KOYA labs logo** used on the landing page. 
- Serves as the primary visual element at the top of the page.

### `CNAME`
- Contains the text `www.koyalabs.ai`.
- Specifies the custom domain for GitHub Pages so that the site is accessible at https://www.koyalabs.ai.

### `fd88876636b744d045b0b81312adec80.html`
- Used for **Twilio domain ownership verification**.
- Contains a verification token: `twilio-domain-verification=fd88876636b744d045b0b81312adec80`.

### `index.html`
- The **main landing page** for KOYA labs.
- Built with **Tailwind CSS**, configured to use the [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono) font. 
- Complies with **WCAG AAA standards** for color contrast.
- Contains the logo, mission and vision statements, and stealth-mode text.

---

## Working With This Repository

Below are instructions for cloning the repository, making changes, and pushing updates.

1. **Clone the repository**

   ```bash
   git clone https://github.com/KOYA-Labs/KOYA-Labs_website.git

This will create a local copy of the repository on your machine.

2. **Create a new branch to implement changes**

   ```bash
   cd KOYA-Labs_website
   git checkout -b my-feature-branch

Replace my-feature-branch with a descriptive name for your changes

3. **Make your edits**

Update index.html as needed.
Add or modify files in the images folder if you have new assets.
If you need to change the domain, update CNAME.
For Twilio verification, ensure the verification file is correct.

4. **Stage and commit your changes**

   ```bash
   git add .
   git commit -m "Describe your changes here"

5. **Push your changes to GitHub**

   ```bash
   git push origin my-feature-branch

6. **Open a Pull Request (PR)**

Go to the GitHub page of your repository fork.
Click Compare & pull request.
Provide a clear description of what your changes do, then open the PR

7. **Merge the Pull Request**

Once reviewed and approved, merge the PR into the main branch.
Your changes will be published to https://www.koyalabs.ai shortly thereafter (GitHub Pages automatically rebuilds).
