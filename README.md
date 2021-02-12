# My Portfolio - Built with MERN Stack. (MongoDB, Express.js, React.js and Node.js)

## Table of Contents

- **[Description](#Description)**
- **[Installation Requirements](#Installation-Requirements)**
- **[License](#License)**
- **[Questions](#Questions)**

# Description
The portfolio website is a clean and minimal site to showcase certain skills and technology used. Built on a MERN stack which utilizes NoSQL using MongoDB to record the information submitted on the Contact Form, Express makes an API call and emails myself upon submission of a contact form, React is the primary framework used for front-end development, built on Node to handle it all. The site follows the MVC design pattern (Model-View-Controller) which is an development architecture style commonly used in software companies. 

 ### Deployed Site @ https://jared-seefrieds-portfolio.herokuapp.com/ 
---
 ![Jared Seefrieds Portfolio](./client/src/images/front-page.jpg)

# Installation Requirements

1. Clone my portfolio in the command line by entering: git clone https://github.com/jaredseefried/my-portfolio.git

2. Install required libraries from entering in the command line: npm i

3. Create .env file at the root directory and enter your gmail credentials for the following process.env values:
    - EMAIL=example@gmail.com
    - PASSWORD=password123
    * API Route is to GMAIL Host only. Change the SMTP Host in ./routes/api/sendmail.js file. Please read the nodemailer documentation on how to properly user your own mail host. https://nodemailer.com/about/ 

4. Update your .gitignore file to include the .env file

5. Start the application by entering in the command line: npm start

6. Your Mongo Database will be created on start and can be viewed through the command line and/or a MongoDB Gui such as Robo 3T https://robomongo.org/. (MongoDB must be installed. If Mongo has not been installed, go to https://www.mongodb.com/2)

# License

MIT

# Have Questions?

## [Github Profile: github.com/jaredseefried](https://github.com/jaredseefried "Title")

Please email me at jared.seefried@yahoo.com if you have additional questions.