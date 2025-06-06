# 🍽️ Eat-n-Split the Bill – React Component

**Eat-n-Split** is a React-based bill-splitting component that helps you track shared expenses with friends. Select a friend, enter the bill details, and split it based on who paid. This project demonstrates essential React concepts like state management, conditional rendering, controlled components, and component reuse.

## Table of contents

- [Overview](#overview)
  - [Features](#features)
  - [Links](#links)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Elements used](#elements-used)
  - [Technologies Used](#technologies-used)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Features

- View and manage a list of friends
- Add new friends with names and avatars
- Select a friend to split a bill
- Enter bill amounts and who paid
- Update balances based on input
- Clear and intuitive UI

### Links 

🔗 -Live Site [Live App](https://maddiepst.github.io/eat-n-split-the-bill/)

### Screenshot

![App Screenshot](./Screenshot%202025-06-06%20115002.png)

## My Process

### Built With

- React (Functional Components + Hooks)
- JavaScript (ES6+)
- HTML5 & CSS3
- Vite (for local development)
- GitHub Pages (for deployment)

### Elements Used

This project allowed me to apply and reinforce several key React concepts:

- ✅ React Hooks
- `useState` for managing local component state (selected friend, form inputs, friend list, balances)
- Functional updates to state when based on previous values (e.g., updating balances)

- ✅ Conditional Rendering
- Show the split bill form only when a friend is selected
- Toggle the friend selection UI

- ✅ Controlled Components
- Form inputs (amounts, who paid) are controlled via state for consistency and predictability

- ✅ Component Composition
- Split the UI into small, reusable components (FriendList, Friend, FormSplitBill)
- Use `children` and props to pass data and customize behavior

- ✅ Child-to-Parent Communication
- Lifted state and used callback props to allow child components (like forms) to update parent state (e.g., selecting or updating a friend)

- ✅ Array Methods
- Used `.map()` to render lists of friends dynamically

- ✅ Dynamic Styling
- Conditional class application to highlight selected friends

### Technologies Used

- React (with Hooks)
- HTML/CSS
- JavaScript (ES6+)
- Node.js (development server)

### Useful resources

- [React Docs](https://react.dev/learn) - Official React documentation and concepts
- [MDN Web Docs](https://developer.mozilla.org/) - HTML, CSS, and JavaScript reference

## Author

- Website: [Madalina Pastiu Portfolio](https://maddiepst.github.io/)
- LinkedIn: [Madalina Pastiu](https://www.linkedin.com/in/madalina-pastiu-52a01396/)
- GitHub: [@maddiepst](https://github.com/MaddiePst)
