## CandidateSearch

## Description

This is a web application that allows employers to search for potential candidates on GitHub and save them to a list of potential hires. This application leverages teh GitHub API to fetch candidate data and provides a simple interface for employers to browse through candidates, accept or reject them, and view the list of accepted candidates. The project is built with React and Typescript for a robust and type-safe development experience.

## User Story

```md
AS AN employer  
I WANT a candidate search application  
SO THAT I can hire the best candidates  
```

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Deployment](#deployment)
- [License](#license)

## Installation

To run the application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/mollyhoward319/CandidateSearch.git
   cd CandidateSearch
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the `environment` folder and add your GitHub Personal Access Token:

   ```bash
   VITE_GITHUB_TOKEN=your_personal_access_token
   ```

   > Note: Follow the instructions [here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-fine-grained-personal-access-token) to create a fine-grained personal access token.

4. Start the application:

   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3001` to see the app in action.

## Usage

When the page loads, the information for one candidate is displayed. You can either save the candidate to the list of potential candidates by clicking the "+" button or skip the candidate by clicking the "-" button. When you add candidates to your list, they will populate on the "Potential Candidates" page. Here you can see all the candidate details. 


## Features

This app fetches data from the GitHub API and displays candidate information. Users can accept or skip candidates from a revolving list. Accepted candidates are saved in local storage and are displayed on a page with all their information. 

## Deployment

The application is deployed on Render. You can visit the live application here: [Candidate Search Application](https://candidatesearch.onrender.comv)

To deploy this application to Render, follow the instructions on [Render's deployment guide](https://coding-boot-camp.github.io/full-stack/render/render-deployment-guide).


## License

Distributed under the MIT License. See `LICENSE` for more information.

## Questions

If you have any questions, contact me at: mollyhoward.developer@gmail.com