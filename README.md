# USYD-project
USYD project 


# Local Server Deployment and Usage Guide for Users

## 1. Deploying the Local Server (Requires Python Pre-installed on Your Computer)

### Steps:

a) Open Terminal. You can do this by pressing **Command + Space** and typing "Terminal"(mac users)/**Win + R**(windows user).

b) Navigate to your project folder using the `cd` command. For example, if your project folder is on the Desktop, type:

```bash
cd ~/Desktop/YourProjectFolder
```

c) Deploy the local server by running the following command:

```bash
python -m http.server 8000
```

## 2. Using the Deployed Server

### Accessing the Web Application:
- Open your web browser and go to http://localhost:8000/. This will open your local web page.

### Web Application Pages:

The web application consists of three main pages:
1. Home Page:
- This is the landing page when you first enter the application. Currently, it is a blank page for
future development.
2. Upload Page:
- Click the upload button at the top navigation bar to enter the upload file page.
- Here, you can upload files that need preprocessing.
- After preprocessing, you can download the processed files by clicking the download button.
3. Classify Page:
Click the classify button at the top navigation bar to enter the classification page. This page has two main functionalities:
### Functionality 1:
- Upload an initial file and click start. The system will automatically preprocess the file.
- Each word will have a dropdown menu below it, allowing you to classify each word into categories (0-8).
- The page provides options to select the number of words displayed per page(100/150/200/300).
- Use the next button to go to the next page for further classification.  Use the save button to save all classified words and download the results as an Excel file.

### Functionality 2:
- Upload an initial file and an Excel file. This is useful if you have previously started classifying a file but did not complete it.
- When you upload both files, the system will continue from where you left off, showing the remaining content for further classification.  his helps you seamlessly continue your work from the last session. By following these steps, you can efficiently deploy and use your local server for file preprocessing and classification tasks.
