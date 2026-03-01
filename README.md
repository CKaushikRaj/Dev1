Project: **The "Auto-Magic"** Portfolio
Goal: Create a simple HTML website that automatically updates on a web server every time you push code to GitHub

**The Tech Stack**
1)Version Control: **GitHub**

2)Cloud Hosting: **Netlify or Vercel (Used Netlify)**

3)CI/CD: **GitHub Actions** (The "glue" that connects them)

Requirements
Before you start, make sure you have the following ready:

**A GitHub Account**: This will be your "Source of Truth" for your code.

**Git Installed**: You'll need to know basic commands like git add, git commit, and git push.

**Basic HTML/CSS**: You don't need to be a designer; a single index.html file saying "Hello World" is enough.

**A Free Netlify or Vercel Account**: These platforms are built specifically for beginners to host sites for free.

 The Step-by-Step Workflow
**1. The Code Phase**
Create a folder on your computer with a simple index.html file.
Local Test: Open the file in your browser to make sure it looks how you want.

**2. The Version Control Phase**
Initialize a Git repository in that folder.
Create a new repository on GitHub.
Push your local code to the GitHub repo.

**3. The Continuous Deployment (CD) Phase**
Log into Netlify/Vercel.
Select "Import from GitHub."
Choose your repository.
**The Magic: Now, every time you change the text in your HTML file and git push, the website will update itself in seconds without you touching the hosting dashboard.
**
**4. The "Pro" Addition (CI Phase)**
To make this a true DevOps project, add a GitHub Action. Create a folder named .github/workflows and add a simple main.yml file that runs a "Linter" (a tool that checks your code for errors).

Now, your pipeline won't just deploy; it will test your code first.
