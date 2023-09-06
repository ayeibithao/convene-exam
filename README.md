# Azeus Convene - Technical Exam
This repository is intended only for Web Developer - Technical Exam

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development exam purposes.

## Instruction:

1. Create a GitHub account
2. Go to the htdocs directory of XAMPP, then clone the Git project via Terminal:

    ```
   git clone 
    ```

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

    Download the latest release of [NVM for Windows](https://github.com/coreybutler/nvm-windows). This will act as the manager of the Node.js versions to be installed on your machine.

    ```
    nvm install 10.15.3
    nvm use 10.15.3
    ```
6. Install Gulp CLI 

    After installing Node.js, install Gulp CLI via npm.

    ```
    npm install -g gulp-cli
    ```

### Running

1. Once you are done with the installation, you may now start running the project.

2. Go to the htdocs directory of XAMPP, then clone the Git project.

    ```
    git clone 
    ```

3. Copy the sample wp-config and create your own copy.

    ```
    cp wp-config-sample.php wp-config.php
    vi wp-config.php
    // ^ Or just edit the file via text editor
    ```

4. Start the MySQL and Apache instances in XAMPP control panel.

5. Open a Web Browser and go to the following URL

    ```
    http://localhost/azeus-convene-wordpress
    ```
### Coding Standards

- Use spaces instead of tabs
- Use two spaces for tab stops

***
