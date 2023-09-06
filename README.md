# Azeus Convene - Technical Exam
This repository is intended only for Web Developer - Technical Exam

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development exam purposes.

## Requirements:

1. Git
2. XAMPP
3. Node.js
4. Gulp (Optional - but highly recommended if you will use SASS for CSS)


### Installing

A step-by-step series of examples that tell you how to get a development env running. Note: Instructions are for Windows setup.

1. Install Git

    For version control, this project will use Git and it is highly recommended to use Git via command-line.

2. Install XAMPP

    Download the latest installer at https://www.apachefriends.org/download.html


3. Install Node.js

   Download the latest release of [NVM for Windows](https://github.com/coreybutler/nvm-windows).
   This will act as the manager of the Node.js versions to be installed on your machine.

    ```
    nvm install 10.15.3
    nvm use 10.15.3
    ```
6. Install Gulp CLI 

    After installing Node.js, install Gulp CLI via npm.

    ```
    npm install -g gulp-cli
    ```

## Instruction:

1. Create a GitHub account and once you are done with the installation, you may now start running the project.
2. Go to the htdocs directory of XAMPP and create a folder file for your exam, then clone the Git project via Terminal:

   Update your Git information first on your local machine:
   
    ```
   git config --global user.name "Your Username"
   git config --global user.email "Your GitHub Email"
   git config --global credential.helper wincred 
   ^ for Password 
    ```

   After you input your detail, Clone the repository at your exam folder (XAMPP - htdocs) 
    ```
     git clone https://github.com/ayeibithao/convene-exam.git
    ```
    
4. Create anew branch for your technical exam:

    ```
   git checkout -b convene-exam#yymmdd (date) - applicant's name (no space and small letters only)

   git checkout -b convene-exam#231017-ayeibithao
    ```
5. Copy the sample wp-config and create your own copy.

    ```
    cp wp-config-sample.php wp-config.php
    vi wp-config.php
    // ^ Or just edit the file via text editor
    ```

6. Start the MySQL and Apache instances in XAMPP control panel.

7. Open a Web Browser and go to the following URL

    ```
    http://localhost/convene-exam
    
    ```
    
5. DO NOT modify directly to "master" branch, you may only makes changes, create files, and modify on your own created branch.
6. FOR SUBMISSION: After you're done with your exam, commit your changes and push.

    ```
    git commit -m "Convene Technical Exam by (Applicant's Name)"
    
    git push
    
    ```
7. Finally, go to GitHub (https://github.com/ayeibithao/convene-exam) and click "Pull Requests" then click "New pull request" button to submit your exam.

### Coding Standards to Follow

- Use spaces instead of tabs
- Use two spaces for tab stops

***
