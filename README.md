<br />

<p align="center">
    <img src="public/logo192.png" width="80" height="80"/>
</p>

<h2 align="center">Cashflow</h2>
<br />

<p align="justify">
    A Progressive web-application (PWA) that helps you track your expenses in an efficient manner using OCR and make you aware of your spending habits using various charts along with additional features of setting goals and reminders
</p>

## Features 

- Great UX by leveraging OCR and OpenCv for text detection and extraction
- Setting monthly goals for specific events like birthdays, etc
- Reminder for fixed expenses  like EMIs, Bills, etc
- Analysis of prev transactions through heatmaps, pie-chart, etc
- Showing user which category has the most expense via stacked bar chart
- Make user aware of its spending habits!

- You can view the backend [here](https://github.com/GreyManuel/cashflow-backend)

## Why our application will give accurate results?

![](public/better-model.png)

- Our model utilizes PyTesseract to find the words such as amount/total/grand total/cash usually found on Kenyan bills/reciept and creating a bounding box around these using openCV
- Since there was low training data available on Kenyan bills coupled with time constraints, we had to rely on third party nanonets API for backup
- We are cross-examining both results and finding the better of the two

## Tech-stack

- React and it's related packages
- Django rest framework
- PyTessearct, OpenCV, RegEx

## Motivation?

- To build something that is relevant to current needs
    - [80% Kenyans Say Covid-19 A Wakeup Call To Fix Their Financial Health]
    - The pandemic broke the age old mirage of job-security and made people swallow the hard pill that concepts like personal finance, budgetting, tracking expenditure are important
-  To build our first PWA

## API
- Nanonets
- GoogleMapsAPI

## Local setup
 
 **1. Clone [server repo](https://github.com/GreyManuel/cashflow-backend) & follow the steps mention [here](https://github.com/GreyManuel/cashflow-backend/blob/master/README.md) to run server locally:-**
 
 **2. Clone this repo by running the following command :-**
 ```
  git clone https://github.com/GreyManuel/Cash-Flow.git
  cd cashflow-frontend
 ```
 
 **3. Now install all the required packages by running the following commands :-**
 ```
  npm install 
 ```
 **4. Now start the react by running the following command :-**
 ```
  npm start
 ```
 **5. Create a `.env` file in the project root folder and copy the format of `.env.sample` file.**

   - `.env.sample` file contains all the environment variables required for running the project.
   
   
 **6.** **🎉  Open your browser and go to  `https://localhost:3000`**


## Author

- **Manuel Grey**
    - [LinkedIn](http://www.linkedin.com/in/manuel-grey-aa4010182) | [Gmail](mailto:greytechsystems@gmail.com) 
## References

[react-calendar-heatmap](https://github.com/kevinsqi/react-calendar-heatmap), [react-chartjs-2](https://react-chartjs-2.netlify.app/), [react-gradient-progress](https://github.com/prasannamestha/react-gradient-progress)
