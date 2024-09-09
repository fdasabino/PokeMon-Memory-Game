# Pokemon Memory Game

- [Click here for live project](https://pokeyourmemory.netlify.app/)

![Game Logo](https://res.cloudinary.com/frank2021/image/upload/v1669823748/pokemon_game/2022-11-30_7_ogcpro.png)

### SUMMARY

- This project has been developed to fulfill the requirements of the Hyper Island Course Goals Skill 2 and Knowledge 2.

#### Knowledge 2:

- Explain how to structure JavaScript files, functions and scopes in the context of web applications and external sources.

#### Skill 2:

- Plan and build a dynamic website that fetches content from API's or a database.

## Application flow

![Flow chart](https://res.cloudinary.com/frank2021/image/upload/v1669640273/pokemon_game/Flow_chart_xmjjop.png)

We have developed a game that fetches data from an API, and displays the data dynamically in order to create a game experience.

Players have to type their name in order to unlock the start game functionality. When 8 card matches are achieved the counter will stop and the player time will be registered in local storage. Thou we do not make use of an external database, it could be something we implement in the future.

## GitHub collaboration

- This project was developed using git version control and github for code collaboration with my support group, which gave us a deeper understanding of the tools available, and how to make better use of gitHub, while working as team.

1.  Contributors:

- We have created a repository where my team members are listed as contributors and have permission to modify the code:

  ![Contributors](https://res.cloudinary.com/frank2021/image/upload/v1669710463/pokemon_game/contributors_gv5hh6.png)

2.  Branching:

- Each team member creates a new branch of the latest main update and adds their version of the code and push to github:

  ![Branching](https://res.cloudinary.com/frank2021/image/upload/v1669640716/pokemon_game/fork_and_branches_hvdn9g.png)

3.  Pull Requests:

- After the code is pushed to github, a pull request is created to check the code pushed for conflicts:

  ![Pull requests](https://res.cloudinary.com/frank2021/image/upload/v1669640716/pokemon_game/pull_requests_yqvh01.png)

4. Merge:

- If no conflicts were found, the code is then merged into the main branch:

  ![Merged code](https://res.cloudinary.com/frank2021/image/upload/v1669898460/pokemon_game/2022-12-01_amd2oe.png)

## Functions

- As part of the projects knowledge goals, we have implemented several functions through out the code base, to help with with separation of
  concerns and better code readability.

![Functions, loops and object manipulation 1](https://res.cloudinary.com/frank2021/image/upload/v1669929007/pokemon_game/fetchfucntion_qj7loh.png)

- The async function declaration declares a function where the await keyword is permitted within the function body. The async and await keywords enable asynchronous, promise-based behavior.

## Loops

- We have also used loops to help on the process of data fetching, in this case we made use of a _while_ loop.

  ![While loop](https://res.cloudinary.com/frank2021/image/upload/v1669897855/pokemon_game/while_loop_g6ro1q.png)

## DOM manipulation

- Once data is fetched, we then saved inside a variable and displayed dynamically on the page, putting to use DOM manipulation, rendering the card element using string literals.

  ![Functions, loops and object manipulation 2](https://res.cloudinary.com/frank2021/image/upload/v1669929007/pokemon_game/display_cards_jsgznv.png)

## API data fetching

- Data is fetched and converted to JavaScript object format.

  ![Functions, loops and object manipulation 3](https://res.cloudinary.com/frank2021/image/upload/v1669803371/pokemon_game/obj_c7dm9w.png)

## File structure

- To better understand JavaScript's file structure we have provided a simple snapshot of the code structure:

1. We have defined all global scoped variables up top, to avoid errors when using strict mode, as well as to make them available to all functions.

![Variables](https://res.cloudinary.com/frank2021/image/upload/v1669810489/pokemon_game/variable_scope_uup9vz.png)

2. We have defined functions according to their use need (Scope) ex. createNewGame() function has been declared at the bottom of the code because it makes use of other helper functions, and variables that have been declared through out the code base.

![createNewGame() function](https://res.cloudinary.com/frank2021/image/upload/v1669809103/pokemon_game/function_scope_pyr72l.png)

- We did not make use of modules in this project, but in the future this can be a feature to implement if the application scales up.

  (JavaScript modules allow you to break up your code into separate files. This makes it easier to maintain the code-base. JavaScript modules rely on the import and export statements.)

## Array and local storage

#### Array and Objects

- Arrays are used to store multiple values in a single variable. Each item in an array has a number attached to it.

- An object is a collection of properties, an association between a key and a value.

- This project also makes use of arrays, and local storage which saves the user data on their machine holding the player scores in a array, displaying a list of scores to the user, also putting into effect DOM manipulation through append/prepend the score board element into the DOM.

  ![Array and local storage](https://res.cloudinary.com/frank2021/image/upload/v1669820157/pokemon_game/score_array_pllfnc.png)

- Data is stored in local storage in a array of objects, and displayed whenever user comes back to the page.

  1. localStorage: data doesn't expire (unless cleaned from browser) => (the one we make use of);

  2. sessionStorage: data is cleared when the page session ends;

  ![Array and local storage 2](https://res.cloudinary.com/frank2021/image/upload/v1669798740/pokemon_game/2022-11-30_sasolq.png)

## Date and time

- We have used the JavaScript Date method to set our timer based functions:

  ![Date time](https://res.cloudinary.com/frank2021/image/upload/v1669821272/pokemon_game/date_time_o7joc5.png)

## Browser developer tools

- We have used Chrome's developer tools to debug our code, as well as dealing with the api data fetching in order to understand how data is returned.

![Developer tools](https://res.cloudinary.com/frank2021/image/upload/v1669799914/pokemon_game/2022-11-30_2_faobic.png)

- We have also used a series of console logs to determine if the application works and runs as it should.

![Developer tools 2](https://res.cloudinary.com/frank2021/image/upload/v1669800471/pokemon_game/clg_eg1pc4.png)

## Feedback from group and mentor

- During the process of development we as group have taken feedback from our mentor, and from within our group for several details and improvements.
  But also from the game jam that happened in the campus on the 29th of November 22. That really helped us with testing and improving the application further.

## SEO and accessibility

- Search engine optimization (SEO) is the practice of orienting your website to rank higher on a search engine results page so that you receive more traffic. The aim is typically to rank on the first page of Google results for search terms that mean the most to your target audience. This application scores a high for SEO and accessibility on Google chrome's lighthouse.

  ![Lighthouse](https://res.cloudinary.com/frank2021/image/upload/v1669640884/pokemon_game/lighthouse_pxwo8b.png)

## Acknowledgments

- This project has taught me how to be better in a work environment and how to collaborate with team members, it was a almost unique feeling to get something built from the ground up together. So I would like to thank my team: [Kevin Johnson](https://github.com/johnsonmkevin) and [Ester Cortes](https://github.com/kristallers) for all the time spent together during the learning process. Also big thanks to Christoffer Teye for the great mentoring skills.
