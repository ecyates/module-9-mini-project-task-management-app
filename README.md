# Module 9 - Mini-Project: Task Management App
Author: Elizabeth Yates

## Introduction

In this Bootstrap-powered Task Management Application project, I embarked on a journey to develop a user-friendly and efficient tool for managing tasks effectively. This project built upon my understanding of HTML and introduced me to the world of Bootstrap, a popular front-end framework for building responsive and mobile-first web projects.

## Pages Folder

In this folder, you'll find the following pages of my task management website that interact with each other to show you an example of how this website would work. 

### Home Page (index.html)

This is the landing page, which includes the following features: 
- Navbar that links you to Home, Task Dashboard, Get Started and collapses into a toggle button when the screen gets small (present on all pages)
- Jumbotron with a welcome message and a relevant background. 
- "Our Key Features" section with cards that feature images in a carousel, a title, and description. 
- Footer with contact information and social media links (present on all pages)

### Task Dashboard Page (task-dashboard.html) 

The task dashboard utilizes accordions, buttons, check boxes, and dropdown menus to create an interactive dashboard for managing tasks. Featuring: 
- A bar on top to customize (button), filter (dropdown), or sort (dropdown) the dashboard. 
- An accordion separating the tasks by category featuring a representative image. 
- Once uncollapsed, it shows the cards that represent each task. The cards show the task name, date, time, and the task owner (as represented by a profile pic). 
- They also feature a red badge if they are checked priority and the user can check the task complete in the card. - Finally, the task cards include a button to view the task details within the card, opening to the Task Detail (task-detail.html) page.
- At the very bottom of the dashboard, there's another "Create New Task" button that takes the user to the Create Task (create-task.html) page.

### Task Details Page (task-detail.html)

This page is designed to show a detailed view of individual tasks. Since it is an example, it doesn't show all of the fields from the task creation form filled in. It exhibits the following features: 
- Header with the category image, name of the task, the profile pic of the task owner, the red circle if the task is "priority", and a pill badge for the category. 
- A card showing the task's date, time, reminders set (with pill boxes showing multiple reminders), notes, and related link. 
- The card also has a "Customize" button in the upper right-hand corner and an "Edit" button in the bottom middle. 

### Task Creation Page (create-task.html)

This page brings the user to the form to create a new task. The header includes a relevant background image and title and brings you straight to the form, which features form validation in addition to the following fields: 
- Task Name (text)
- Task Category (dropdown menu)
    - Personal Development
    - Finance
    - Social/Community
    - Shopping
    - Travel
    - Education
    - Pets
    - Hobbies/Leisure
    - Home
- Date (date)
- Time (time)
- Send Reminder (Select multiple dropdown menu) 
    - None
    - 5 Mins Before
    - 15 Mins Before
    - 30 Mins Before
    - 1 Hour Before
    - 1 Day Before
    - 2 Days Before
    - 1 Week Before
- Notes (textarea)
- Related Link (url)
- Choose File (file)
- Check to Prioritize (checkbox)
- Submit button

### Authentication Form (authentication-form.html)

If you click the "Get Started" link in the navbar, it will take you to this authentication form. 
- This is a simple username/password form for those who already have an account. 
- If you don't have an account, you can click the "Create Account" link in the header and it will take you to the Registration Form (registration-form.html) page. 
- There's also a "Forgot password?" link under the submit button. 

### Registration Form (registration-form.html)

The registration form has two sections: 
**Contact Information**
- First Name (text)
- Last Name (text)
- Email (email)
- Phone Number (tel)
**Account Information**
- Username (username)
- Password (password)

The form includes form validation to ensure the correctness of user-provided information. Upon submission, the form will take you to the Thank You (thank-you.html) page.

### Thank You Page (thank-you.html)

This is a simple page, thanking the user for registering (featuring a background image and header) and providing them with a button to "Get Started" that will take them to the Create Task (create-task) page. 

## Images Folder

All images were sources from www.unsplash.com so I'd like to extend a very special thank you to all the amazing photographers and designers over there. I included various images that I ended up not using for the different categories but if I were to build out the functionality of this project more, I'd need to include those images, so I'll leave them there. 

## Styles Folder

In addition to using the Bootstrap framework, I included a styles.css page to help with hovering over particular links, specifically in the footers, the plain links on the authentication form, and the checked boxes on the forms. 



*This code can be found in this repository:*
*https://github.com/ecyates/module-9-mini-project-task-management-app.git*