#Contact Page
<h1 align="center" id="title">Contact Page</h1>

<p align="center"><img src="https://socialify.git.ci/vaibhavdudhal/Contact_Form/image?font=Inter&amp;language=1&amp;name=1&amp;owner=1&amp;stargazers=1&amp;theme=Light" alt="project-image"></p>

<p id="description">This repository contains a simple contact page built with React. Users can fill out the contact form with their name email phone number and message. Upon submission the data is sent to a Google Sheets spreadsheet for easy management and tracking.</p>

<h2>Project Screenshots:</h2>

<img src="https://drive.google.com/file/d/1ErLmshHteQT46m-LyDnIdkENHUHYP_79/view?usp=sharing" alt="project-screenshot" width="400" height="400/">

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   User-friendly Interface: Simple and intuitive interface for easy user interaction.
*   Form Validation: Ensures data accuracy and reduces errors through input validation.
*   Google Sheets Integration: Stores and organizes form submissions in Google Sheets for easy management.

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the repository: Open a terminal or command prompt and navigate to the directory where you want to clone the project. Then run the following command:</p>

```
git clone https://github.com/vaibhavdudhal/Contact_Form
```

<p>2. Install dependencies: Navigate to the project directory: Bash</p>

```
cd Conatct_Form
```

<p>3. Then install the project's dependencies using npm:</p>

```
npm install
```

<p>4. Alternatively if you prefer using yarn run:</p>

```
yarn install
```

<p>5. Create a NoCode Google Sheets API account: Go to https://nocodeapi.com/docs/google-sheets-api/ and create a free account. Follow the instructions to connect your Google account and create an API for your Google Sheet. Remember the API endpoint URL provided by NoCodeAPI.</p>

<p>6. Set up constant variables: In constant.js file the replace GOOGLE_SHEET_URL with the your endpoint URL from NoCodeAPI</p>

```
GOOGLE_SHEET_URL=YOUR_API_ENDPOINT_URL
```

<p>7. Start the Development Server: Run the development server to preview the project locally.</p>

```
npm start
```
