# Create a note-taking web app using Typescript and React

The goal of this task is to create a simple note-taking web app inspired by Google Keep.
The web app will communicate with an API to get a list of notes as well as being able to update/delete a note.

It must support routing and handle not found page properly.

## Acceptance Criteria

1. A fake API server should be setup.
    - Recommended: [json-server](https://github.com/typicode/json-server)

2. The web app is setup using __Typescript__, React, and its commonly used library.
    - The main functionality includes:
        - Show a list of notes
        - Create a new note
        - Edit a note
        - Delete a note
        - All actions __MUST__ communicate with the API.
    - Other functionality:
        - Support routing (When refreshed, it should stay on the same page)
        - An example of the routes:
            - Home page: `/` or `/home`
            - Create a new note: `/new`
            - Edit a note: `/notes/{id}/edit`
            - About page: `/about`
            - Not found page: `/sth-random`
    - The mockup is provided only as reference. The final result should look like a real web app.

3. There should be no CSS library/framework involved. SCSS can be used. BEM methodology is preferred.

4. The solution should be put in a git repository and there must be instructions on:
    - How to run the mock API server
    - How to run the frontend

## Bonus
1. Clean code, proper folder structure, and documentation
2. Good design and animation
3. Server-side rendering is supported
4. Containing unit tests and/or end-to-end tests


## Mockup for Reference

### Home Page
- A note can be deleted via the dropdown.

![home](assets/home.png)

### Create a note
- Clicking on "Take Note" will expand the container and allow the user to input "title" and "description".

![new](assets/new.png)

### Edit a note
- Clicking on a note will show a modal that allows the user to edit title and description after clicking "Update".

![edit](assets/edit.png)

### About page

![about](assets/about.png)

### Not found page

- When accessing a page that does not exist, there should be a proper not found page.

![not-found](assets/not-found.png)