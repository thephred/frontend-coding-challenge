# Frontend Coding Problem

This is an Single Page Application (SPA) + HTML / CSS coding problem. This task is divided in 4 parts. First 3 are mandatory and 4th part is a bonus task. Put your code on Github and submit a repository link. 

## 1. Implement Responsive Design

1. Implement design of `Dashboard.jpg` attached using a CSS framework (like Bootstrap). Cards data is provided in `cards.json` attached
2. The design should be responsive down to iPhone 5. You are not provided mobile designs. Please implement responsive design according to your own intuition
3. Design and implement Campaigns selection dropdown (List of campaigns is provided in `campaigns.json` attached

_Pending, Search, Data buttons do not need to be functional_


What we are looking for:

* Attention to detail. Please make the desktop design as close to provide JPG as possible
* HTML structure
* Structure for CSS classes
* Your own design sense

## 2. Implement Functionality of Campaigns Filter

Use a SPA framework of your choice (like React) to implement the funcationality of the campaigns filter. User should be able to filter cards shown based on the selected campaign. Dropdown should also provide "All Campaigns" selection which should show all campaigns. Please implement a component based structure. Use campaign ID field in `cards.json` and `campaigns.json` to correlate cards with selected campaign. The rest of fields on the card need not to be functional. 

What we are looking for:

* Sense of App structure in a SPA framwork
* JavaScript/Typescript coding style and structure

## 3. Implement Functionality of Moving Cards Between States

The cards are in one of the following states: `'saved','pending','active','paused','expired','declined','terminated'` based on the value in the `currentWorkflow` field. Implement functionality that moves the cards between states. Mock this (or as bonus in #4 implement this) as a process that takes 5+ seconds to complete. The state diagram is as follows:

![State Diagram](/state-diagram.png)

What we are looking for:

* The ability to move items through a set of states.
* Seing how well user (micro) interactions are handled (especially when completion of the interaction is not instant)

## 4. (Bonus) Implement basic NodeJS express server

Instead of hardcoding `campaigns.json` and `cards.json` in frontend, put them at backend and write API's to fetch campaigns dropdown data and cards from backend. 

What we are looking for:

* RESTful use of API's
* Usage of API's on the client side

