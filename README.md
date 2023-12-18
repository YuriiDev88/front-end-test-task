## 🚀 Task
The main task is to create a page for viewing information about characters from the "Rick and Morty" series. As a user, I should be able to view all characters, detailed information about a selected character, and use a filter to quickly find a specific character from the entire list of proposed characters. Additionally, my actions on the site should be recorded in a history that I can later review.
<br>

## 📎 Links
**Design**: Figma

**API Documentation**: Docs

<br>
## 🛠 Technologies
⚡️ **Base**

- ```TypeScript```
- ```React``` 

⚡️ ** State Manager and Middleware**

- ```Redux Toolkit```
- ```Redux Thunk```

⚡️ **Routing**

- ```React Router```

⚡️ **Request Handling**

- ```GraphQL```

⚡️ **Form Handling (choose one)**

- ```Formik``` 
- ```React Hook Form```


⚡️ **UI Libraries (choose one)**

- ```Material UI```
- ```Ant Design```

⚡️ **Styling (choose one)**

- ```styled-component```
- ```Стилізація методами вибраної UI бібліотеки``` 
- ```SASS/SCSS/LESS modules```

⚡️ **Code Validation and Formatting**

- ```ESLint``` 
- ```Prettier``` 

> You can use only ESLint (for validation and formatting) or in combination with Prettier.

> All libraries should be of the latest version.

📌 Task Execution Order
Complete the task using the specified technologies and following all the points described above.
Place the completed test task in your Git repository (committing frequently is a good practice).
Deploy the completed project. You can use GitHub or Firebase, but this list is not exhaustive. (This step is optional but a plus)
Inform about the task completion and provide a link to the Git repository and the deployed project (if applicable).
🖥 Happy hacking!



## 👩‍💻 Technical Aspects

1. The website should have 2 pages: 
   1) **Home**
      - has to contain the list of characters (as designed in Figma), filters block, header and footer;
   2) **Character**
      - shows detailed review page with detailed character's informartion;
2. In the bottom-right corner, there should always be a FAB, containing 2 options:
   1) **History**
      - on user click the Drawer has to be open;
      - drawer shows search history with filter parameters is recorded;
      - history information has to be preserved after page reload;
   2) **Download**
      - on user click downloads a .csv file with characters which are on the specific page in pagination under filter parameters;
3. **Filters block**
   1) should allow user to filter the `characters` by three parameters - `Character, Location, Episode`;
   2) each choosen parameter should add it's corresponding fields for filtering;
   3) should include the `find` button to initiate a request to the API;
   4) user should be able to clear added filters and see the list without filters;
   5) filters should be kept after requests, so user should be able to change his previous settings in filters block;
   6) each request data for filters should be shown into the **History**; 
4. **Character card**
   1) character card has to show user the fields according to the design;
   2) on clicking the characters name, user should be redirected to the character page;
   3) the displayed information is at your discretion, but show not less than 5 fields of different character data;
   4) clicking action should be recorded in the **History**. It will be enough to write "Viewed information about <character's name>";
   5) on the character page, the Download button within FAB should be inactive;
5. If you decided to work with the REST API for this task, use Redux only. If you choose GraphQL, you can just go on with the Apollo client

<br>

## 📌  What will we assess:
* workability: how your application works;
* project structure: how you structure your files;
* code quality: how you write clean, readable code (feel free to install and use ESLint and Prettier);
* knowledge of technologies and their ecosystem: how you compose and use libraries together;
  
## 📌 Task Execution Order

* Complete the task using the specified technologies and following all the points described above.
* Place the completed test task in your Git repository (committing frequently, and writing clear, understandable commit messages is a good practice).
* Deploy the completed project anywhere you want.
* Inform about the task completion and provide a link to the Git repository and the deployed project.



🖥  Happy hacking!
