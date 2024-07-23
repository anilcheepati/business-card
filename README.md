# React + Vite + GitHub + Netlify(deployment purpose)


# Business Card

## Static Site Built with React JS

This project is a static site built using React JS, showcasing key concepts and the structure of a React application and adding this project in Github by creating new repo and then deploying in netlify.

## Key Concepts of React

- **React**: A powerful JavaScript library for building user interfaces, particularly single-page applications, enabling the creation of dynamic and interactive web experiences.
- **Declarative**: Allows developers to describe what the UI should look like and let React handle the details.
- **Imperative**: Involves describing how to achieve each step, which is less common in React's approach.

## Components

Components are the core building blocks of React applications. They can be either functional or class-based. In this project, separate components were built for different parts of the site:

- **Info**: Displays a photo, name, and buttons.
- **About**: Provides information about the site or person.
- **Interests**: Lists interests or hobbies.
- **Footer**: Contains footer information.

## Requirements

To run this project locally, ensure you have the following:


- Node.js and npm installed
- React and other dependencies specified in `package.json`
-Sign up in Netlify

## Installation

1: Create one folder and open that folder in vscode , go to ternimal and add this command --> npm create vite@latest 

2: It will ask for Project Name type it , once you done it will ask for select Framework select--> (REACT) and will ask for select variant select--> (Javascript) and it will upload all the dependency's in your project name folder.

3: Navigate to the project directory: `cd your-repo-name`

3: Install dependencies: `npm install`

4: Start the development server: `npm start`

5: In your Github create a new repository

6:Clone the repository:
   `git clone https://github.com/yourusername/your-repo-name.git`

7: If you want to work both on Github and Netlify , go to this webpage (https://vitejs.dev/guide/static-deploy.html#github-pages) and make changes in vite.config.js file 

8: Go to vite.config.js file and add --> base: "./" under plugin line and save it add it to your repo

9: Next Go to Your repo settings , on your left side you see pages click on it , then you see Build and deployment drop box select select --> Github Actions once you click on that under the button you see--> [create your own] by clicking on that you will navigate to your-repo-name/github/workflow// [ type --> deployment.yml ] and edit the below file with the content(means in the webpage you will have to copy the step 2 and paste it in deployment.yml file) in this webpage (https://vitejs.dev/guide/static-deploy.html#github-pages)

10: Click on commit changes , then click on action there you can see build your project workflow once it is successfull go back to main page of your repo there right side below you will see Environment (github_pages) click on that it will give an link click on that you see your project webpage in google chrome.

11: pull the changes to your local machine ( your project folder) that you commit changes in github , go to vscode your project folder under cd projectName/ open in terminal then type git pull it will add deployment.yml file into your project folder.

## Deploying into Netlify

1: Create a account

2: Connect to your Github

3: Then add your repo into Deployment then it will generate a netlify link , copy that and paste it in chrome is can see your app.


