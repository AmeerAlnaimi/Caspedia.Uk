<div align="center">
  <img src="readme_images/repository-open-graph-template.png" width="50%" alt="Repository Open Graph Template">
</div>

<div align="center"><h1>
  <img alt="GitHub Release Date" src="https://img.shields.io/github/release-date-pre/ameeralnaimi/caspedia.uk?style=plastic">
  <img alt="Static Badge" src="https://img.shields.io/badge/HTML-Powered-yellow?style=plastic">
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/ameeralnaimi/caspedia.uk?style=plastic">
   <a href="LICENSE"><img alt="GitHub License" src="https://img.shields.io/github/license/ameeralnaimi/caspedia.uk?style=plastic">
  <a href="LICENSE-CC-BY-SA.txt"><img src="https://img.shields.io/badge/Content_License-CC_BY--SA_4.0-lightgrey.svg?style=plastic" alt="License: CC BY-SA 4.0"></a>
  
</div></h1>

<p align="center">
Student-run digital encyclopedia dedicated to documenting and preserving community events; <strong><a href="http://caspedia.uk" target="_blank">Caspedia.Uk</a></strong></a>
<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#repository-structure">Repository Structure</a> •
  <a href="#contribute">Contribute</a> •
  <a href="#credits">Credits</a> •
  <a href="#related">Powered By</a> •
  <a href="#license">License</a>
</p>

# Key Features

* **Classic Wiki UI:** Formatted with a clean, distraction-free aesthetic using traditional academic typographic scales (featuring *Linux Libertine Display*, *Linux Biolinum*, and *Georgia*).
* **Live UAE Time Tracker:** A native JavaScript engine that hooks into the `Asia/Dubai` timezone to display a real-time, ticking clock for local campus schedules.
* **Privacy-First Analytics:** Features seamlessly integrated, lightweight telemetry via **GoatCounter** and **Cloudflare Web Analytics** to track page views ethically without tracking student data.
* **Fully Responsive Architecture:** Designed from the ground up with native CSS variables to ensure perfect readability on desktop monitors. (Mobile compatibility will be added soon!)


# Repository Structure

```text
├── index.html            # Main landing page & wiki homepage
├── statistics.html       # Analytics dashboard & public metrics
├── Cas_Junior_Logo.svg   # Official platform branding assets
├── LICENSE               # Software license (MIT)
└── LICENSE-CONTENT.txt   # Content distribution license (CC BY-SA 4.0)
```
# Contribute

There are three ways to contribute to the development of Caspedia.Uk, and each way has its own specific methods.

### 1. Software Contribution
 
If you want to contribute directly to the codebase — fixing layout issues, improving styling, adding features, or updating pages — follow the standard **Fork → Clone → Branch → Commit → Pull Request** workflow.

**Step 1 — Fork the repository**
 
Click the **Fork** button on the top right of the repository page to create your own copy.
 
**Step 2 — Clone your fork locally**
 
```bash
git clone https://github.com/ameeralnaimi/Caspedia.Uk.git
cd Caspedia.Uk
```
 
**Step 3 — Create a new branch**
 
Always work on a new branch, never directly on `main`.
 
```bash
git checkout -b your-branch-name
# Example:
git checkout -b fix/footer-links
```
 
**Step 4 — Make your changes**
 
Edit the relevant HTML/CSS files in your code editor (e.g. VS Code).
 
**Step 5 — Stage and commit your changes**
 
```bash
git add .
git commit -m "Brief description of what you changed"
# Example:
git commit -m "Fix broken contact link in footer"
```
 
**Step 6 — Push your branch to GitHub**
 
```bash
git push origin your-branch-name
```
 
**Step 7 — Open a Pull Request**
 
Go to your fork on GitHub and click **"Compare & pull request"**. Write a clear description of what you changed and why, then submit.
 
> Your pull request will be reviewed by **Ameer M. Alnaimi**. Please be patient — Caspedia currently has one maintainer.

 ### 2. Article Suggestion / Contribution
 
If you would like to suggest or contribute a new article or page to Caspedia.Uk, **do not open a blank Pull Request**. Instead, submit your suggestion through the GitHub Issues page using the correct template.
1. Go to: **[https://github.com/AmeerAlnaimi/Caspedia.Uk/issues](https://github.com/AmeerAlnaimi/Caspedia.Uk/issues)**
2. Click **"New Issue"**
3. Select the **"Article Suggestion"** template — do **not** click "Blank Issue", as it will be swiftly ignored
4. Fill in the template with as much detail as possible about the article you are proposing

### 3. Bug Report
 
If you have found a bug, broken link, display issue, or any other problem on Caspedia.Uk, please report it using the form below.
