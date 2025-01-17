<div align="center">
<h1 align="center">
  Autofill Jobs
</h1>
  <p>
  A chrome extension that autofills job applications, built with 
  <a href="https://vuejs.org/">Vue</a>.
</p>
</div>

## Why I made this 

Job applications, especially on platforms like Workday, take way too long to fill out (up to 20 mins!)

I wanted to bring the ease-of-use of LinkedIn Easy Apply to other job platforms.



## How it works ✍️

 - Data is stored using chrome.storage.sync with the exception of large files like résumés, which are stored with chrome.storage.local
 - Depending on platform (Greenhouse uses React components, Lever does not) the extension fills in the fields with the data

## Getting Started 🚀
You can either build the extension locally:
```
# Clone the repository
git clone https://github.com/andrewmillercode/Autofill-Jobs.git

#Go to source directory
cd src

# Install required packages
npm i 

# Build extension
npm run build

# Then, navigate to chrome://extensions and load unpacked the dist folder.
```
Or download it from the Chrome Web Store (coming soon)
