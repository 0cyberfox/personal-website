# Personal Website

This is my personal website. I originally hosted it on an Apache server running on an AWS EC2 instance. Now it's deployed using GitHub Pages for always-on hosting.

## Live Demo
You can view the live site here:  
https://0cyberfox.github.io/personal-website/

## Project Structure
VPC/
├── index.html          # Homepage
└── resources/
    └── css/
        └── style.css   # Stylesheet

## Deployment
The website is hosted using GitHub Pages.

How it was deployed:
1. Created a public GitHub repository.
2. Pushed the HTML and CSS files into the repo.
3. Enabled GitHub Pages in Settings → Pages.
4. The site is now live at the link above.

## Technologies Used
- HTML  
- CSS  
- GitHub Pages for hosting

## Background
I initially ran this website on an Apache server inside an AWS EC2 instance, which was part of a manually created VPC. This project is part of my learning journey with cloud engineering and web development.

## Next Steps
- Automate AWS infrastructure setup using Terraform.
- Deploy the website using an automated pipeline instead of manual setup.