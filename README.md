<div align="center">

  https://github.com/user-attachments/assets/a0f56b50-bad9-4b4d-89ad-58fe1aac9852

<h1 align="center">
  Job Applications Autofill
</h1>
  <p>
  A Chrome extension that autofills job applications, built with 
  <a href="https://vuejs.org/">Vue</a>.
</p>
</div>

## Description
Job applications, especially on platforms like Workday, take way too long to fill out. I wanted to bring the ease-of-use of LinkedIn Easy Apply to other job platforms.

Data is stored using chrome.storage.sync with the exception of larger files like résumés, which are stored with chrome.storage.local. Depending on platform (Greenhouse uses React components, Lever does not) the extension fills in the fields with the data. On Workday, ensure you have the tab open in full screen as some essential elements don't get rendered on smaller resolutions.

## Supported Platforms
 - Greenhouse
 - Lever
 - Dover
 - Workday

## Getting Started
You can either build the extension locally:
```
# Clone the repository
git clone https://github.com/m-wilkosz/job-applications-autofill.git

# Go to source directory
cd src

# Install required packages
npm i

# Build extension
npm run build

# Then, navigate to chrome://extensions and load unpacked the dist folder.
```
Or download it from the Chrome Web Store (coming soon)

## License

This project is using the MIT License. If you'd like to report an issue with the extension, please use the issues tab.
