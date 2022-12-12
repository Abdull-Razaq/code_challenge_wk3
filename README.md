 ## Description
This is a code challenge meant to test on skills acquired upto the current stage of the Software-Engineering course work

 ## Running The Live Hosted Application
On your browser open this link to access the live web application

 ## Running Application on Local Server
   ## Getting Started
In order for you to use the content on this repo ensure you have the following:

A computer that runs on either of the following; 
    (Windows 7+, Linux, Mac OS)
    nodejs 9.0+

 ## Installation
To use this repo on your machine requires some simple steps

 **Alternative One**
Open a terminal / command line interface on your computer

Clone the repo by using the following to create a copy on your local machine:

  git clone https://github.com/Abdull-Razaq/code_challenge_wk3 
    Change directory to the repo folder:
    cd l1-js-dom

(Optional) Open it in Visual Studio Code

    code .
    (Alternate Option) Open it in any editor of your choice.

  **Alternative Two**
On the top right corner of this page there is a button labelled Fork.

Click on that button to fork the repo to your own account.

Take on the process in Alternative One above.

Remember to replace your username when cloning.

  git clone https://github.com/your-username-here/code_challenge_wk3 

## Running the application
To run the application, you can use the following steps to run the app.

## Install required dependencies from npm

    npm install
    Run the application
    npm start

## Brief challenge description
   **Requirements**
For this project, you must:
    Have a well-written README file.
    Fetch data from a local server running JSON DB server.

   **Project Setup**
Once you have the plan in place for the application you want to build take the following steps:

    Create a new project folder.
    Create a new GitHub repository (NB: ENSURE IT IS PUBLIC)
    Add your TM as a contributor to the project. (This is only for grading purposes. We promise we won't steal your code)
    Please make sure you regularly commit to the repository.

  **Core Deliverables**
As a user, I can:

    See the first movie's details, including its **poster, title, runtime,showtime, and available tickets** when the page loads. The number of available tickets will need to be derived by subtracting the number of `tickets_sold` from the theater's `capacity`. You will need to make a GET request to the following endpoint to retrieve the film data:

     See a menu of all movies on the left side of the page in the `ul#films` element when the page loads. (_optional_: you can style each film in the list by adding the classes `film item` to each `li` element.) There is a placeholder `li` in the `ul#films` element that is hardcoded in the HTML —feel free to remove that element by editing the HTML file directly, or use JavaScript to remove the placeholder element before populating the list. You will need to make a GET request to the following endpoint to retrieve the film data:

     Buy a ticket for a movie. After clicking the "Buy Ticket" button, I should see the number of available tickets decreasing on the frontend. I should not be able to buy a ticket if the showing is sold out (if there are 0 tickets available). 



  **Authors**
This project was contributed to by:
## Abdirizak Mohamed.

## MIT License

 **Copyright (c) 2022 Abdull-Razaq**

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
