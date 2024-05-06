# Taiyo-ai Assesment

## Tech stacks used:
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
![React-Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&amp;logo=react-router&amp;logoColor=white)
[![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![Axios](https://img.shields.io/badge/Axios-5E8EEA?style=for-the-badge&logo=axios&logoColor=white)](https://axios-http.com/)
![Javascript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&amp;logo=javascript&amp;logoColor=F7DF1E)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&amp;logo=react&amp;logoColor=61DAFB)
![Redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&amp;logo=redux&amp;logoColor=white)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![React-Leaflet](https://img.shields.io/badge/React--Leaflet-88C057?style=for-the-badge&logo=React&logoColor=white&labelColor=88C057)](https://react-leaflet.js.org/)
<h1>A Contact Management App with Charts and Maps of Covid Cases all over the World.  
<h1>What is the task assigned by Taiyo.AI ?</h1>
<ul>
<li>Create a Contact Management app with Charts and Maps using ReactJS, TypeScript,
TailwindCSS, React Router v6 and React Query aka TanstackQuery</li>
<li>Create a GitHub/GitLab repo and possibly deploy your app on free services like Vercel, Github
Pages or Heroku etc</li>
</ul>
<h1>Objectives of Contact Page</h1>
<ul>
    <li>The app should have a form for adding new contacts.
    </li>
    <li>The app should display a list of all added contacts</li>
    <li>
    Each contact should have a button to view the contacts details
    </li>
    <li>
    The app should be able to edit and delete contacts
    </li>
    <li>
    Make use of Redux to store the contact data
    </li>
    
</ul>
<h1>Objectives of Charts and Maps Page</h1>
<ul>
    <li>Build a simple dashboard with:
    </li>
    <li>- A line graph showing the cases fluctuations</li>
    <li>
    - A react leaflet map with markers that indicates the country name, total number
    of active, recovered cases and deaths in that particular country as a popup
    </li> 
</ul>



<h1>Technologies Used</h1>
<ul>
    <li>ReactJs
    </li>
    <li>TypeScript</li>
    <li>
  TailwindCSS
    </li> 
    <li>React Router v6
    </li>
    <li>React Query</li>
    <li>
    Redux
    </li> 
</ul>

<h1><strong> Development Installation </strong></h1>

Follow these instructions to set up your development environment, which you need to do before you start contributing code to this project.

<h1><strong> Manual Installation </strong></h1>

_Note_: The installation steps assume you are using a Unix-like shell. If you are using Windows, you will need to use `copy` instead of `cp`.

1. Install Node.js. The recommended way is to Node through [nvm](https://github.com/nvm-sh/nvm). You can also install [node.js](https://nodejs.org/download/release/v18.2.0/) version 18.2.0 directly from the Node.js website.
2. [Clone](https://github.com/Gobind557/Covid-tracker-taiyo.git) your new fork of the repository from GitHub onto your local computer.

   ```
   $ git clone https://github.com/Gobind557/Covid-tracker-taiyo.git
   ```
3. Navigate to root directory and implement the following commands :

   ```
   
   $ npm install
   $ npm run start
   ```
## Pages:
- `/`Chart page 
- `/contacts` contactpage 



<h1>APIs Used</h1>
<ul>
    <li>World wide data of cases: https://disease.sh/v3/covid-19/all
    </li>
    <li>Country Specific data of cases: https://disease.sh/v3/covid-19/countries</li>
    <li>
   Graph data for cases with date: https://disease.sh/v3/covid-19/historical/all?lastdays=all
    </li> 
</ul>

## GET requests returns historic data regarding active cases, deaths and recoveries (COVID 19)

## 1. URL: https://disease.sh/v3/covid-19/historical/all?lastdays=all

cases:{
    ['1/2/2022',89] 
    ...
}
deaths:{
    ['1/2/2022',89]
    ...
}
recovered:{
    ['1/2/2022',89]
    ...
}

## GET request return object containing country specific information regarding covid 19

## 2. URL: https://disease.sh/v3/covid-19/countries

[
    {
        country:String,
        active:Number,
        deaths:Number,
        recovered:Number
        ...
    }
    ...
]

## GET request return object containing world wide information regarding covid 19

## 3. URL: https://disease.sh/v3/covid-19/all

    {
        total:Number,
        active:Number,
        deaths:Number,
        recovered:Number
        ...
    }
 # Showcase
![Screenshot 2024-05-06 175420](https://github.com/Gobind557/devSpace/assets/72307219/825cc44b-9c88-4ce8-ad05-897401b18731)
![Screenshot 2024-05-06 175400](https://github.com/Gobind557/devSpace/assets/72307219/5b847e63-b287-457f-b689-3ee7f4dcb8d1)
![Screenshot 2024-05-06 175444](https://github.com/Gobind557/devSpace/assets/72307219/3ca083f8-bf47-4dfe-9db0-af3cf2c1c9b3)
![Screenshot 2024-05-06 175453](https://github.com/Gobind557/devSpace/assets/72307219/89b40541-34cc-428b-a44f-20897c93dbc8)

