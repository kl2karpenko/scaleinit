# World Clock and Timer APP

As a UI inspiration you can use one of this:
- https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRK89x2YSRxK9duyCZe7d-y62vu3qLnPq8Xhw&usqp=CAU
- https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLLnOaKWiESdrvruNvF-mzzEMxQfV3hi91_g&usqp=CAU

## Requirements

- Create **World Clock and Timer App** that includes
  - 2 pages with Tabs on the top (each tab text inside is a url to the page)
      - World Clock
      - Timer App
  - Each tab will redirect user to a page accordingly - World Clock or Timer 
- "World Clock" page contain
    - Page title "World Clock"
    - Add button on the right in the title
      - On click we should open a Create new timezone dialog
    - "Create new timezone" dialog
      - Title "Add new timezone"
      - Select with the list of timezones
      - Button "Add"
    - List of default timezones + the ones that user will add
      - Each item in list contain
        - Name of timezone
        - Time in that timezone
        - time difference between user timezone and timezone in the list
        - Button to remove this timezone
- "Timer" page contain
  - 3 inputs (hour/minutes/seconds)
  - button "Start"
    - On click timer starts, inputs become readonly and the time changes there each second accordinly
  - button "Reset"
    - On click inputs become writable and time sets to 0 in each input
  - Select with a list of sounds for the timer end
  - When timer ends
    - selected by user sound should play for 30 seconds and than end
    - inputs become writable and time sets to 0 in each input

## Additionally 

- You can add Drag and Drop Features for this App, so that:
  - you can change the order of tasks in both lists
  - you can drag and drop items from one list to another

**Requirements**

- Create this application using **React/Typescript/JS/HTML/CSS**
- Optionally use window **localStorage/sessionStorage** to save added timezones by user
- Add at lest some unit test for FE using Jest

Application repo should have next scripts, in order to check how it works:

`lint` (using eslint) <br />
`build` (a build version) <br />
`test` (to run tests) <br />
`start` (to run application locally) - this should start the FE webpack to rebuild app on changes + this should start a backend NODEJS server <br />

### Which technologies will be covered in this task:

* Webpack
* Eslint
* JS/HTML/CSS
* DEMO the project results
* AGILE practise
* React
* Create React App
