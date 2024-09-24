![Travel Packing List](https://raw.githubusercontent.com/sanicodeplayground/portfolio-sanita/main/public/images/projects/portfolioTravelList.png)

# 🏝️ Far Away ✈️

**What do you need for your 😍 trip?**

Far Away is a user-friendly travel packing list application designed to help you organise and track items for your upcoming adventures.

[**Live Demo →**](https://travel-packing-list-one.vercel.app/)

## Table of Contents

- [Project Goal](#project-goal)
- [Job Story](#job-story)
- [Project Scope](#project-scope)
- [Features](#features)
- [How to Use](#how-to-use)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Challenges](#challenges)
- [Testing](#testing)
- [Credits](#credits)
- [Learning and Takeaway](#learning-and-takeaway)
- [Personal Reflections](#personal-reflections)
- [License](#license)

## Project Goal

The primary goal of the Far Away project is to create a simple yet effective tool for travelers to manage their packing lists. It aims to reduce the stress of packing by providing an easy-to-use interface for adding, tracking, and organising travel items.

## Job Story

When I'm preparing for a trip, I want to easily create and manage a packing list so that I can ensure I don't forget any essential items and can track my packing progress.

## Project Scope

### Now

- Implement core functionality: adding items, marking as packed, deleting items
- Create a user-friendly interface
- Implement sorting and list clearing features
- Add real-time packing progress tracker
- Implement data persistence using local storage

### Then

- Add categories for items (e.g., clothing, toiletries, documents)
- Implement drag-and-drop functionality for reordering items

### Later

- User accounts and cloud sync
- Shareable packing lists
- Suggested items based on destination or trip type

## Features

- Add items to your packing list with quantity and description
- Mark items as packed or unpacked
- Delete individual items
- Sort items by input order, description, or packed status
- Clear the entire list with confirmation
- Real-time packing progress statistics
- Data persistence using local storage
- Responsive design for various screen sizes

## How to Use

1. Enter the item name in the input field and select the quantity (1-20)
2. Click "Add" or press Enter to add the item to your list
3. Use the checkbox to mark items as packed
4. Click the "❌" button to remove an item
5. Use the sorting dropdown to organise your list by input order, description, or packed status
6. Click "Clear list" to remove all items (with confirmation)
7. View your packing progress at the bottom of the page

## Technologies Used

- ##### React (v18+)
  - was used for ease of state management.
- ##### Vite
  - was used as a build tool.
- ##### JavaScript (ES6+)
  - was used for core functionality.
- ##### CSS3
  - was used to style my entire project.
- ##### Git
  - was used for implementation and version control.
- ##### GitHub
  - was used for the storing of the repositiory.
- ##### Local Storage API
  - was used for data persistence.
- ##### React Hooks
  - useState and useEffect
- ##### Vercel
  - was used to deploy the project

## Installation

1. Clone the repository
   ```
   git clone https://github.com/sanicodeplayground/travel-packing-list.git
   ```
2. Navigate to the project directory
   ```
   cd far-away
   ```
3. Install dependencies
   ```
   npm install
   ```
4. Start the development server
   ```
   npm start dev
   ```

## Challenges

During the development of the Far Away travel packing list application, several challenges were encountered and overcome:

##### State Management:

Implementing a clean and efficient state management system using React hooks (useState and useEffect) to handle the list of items, their packed status, and sorting preferences.
Ensuring that state updates were performed correctly, especially when toggling item status and reordering the list.

##### Data Persistence:

Implementing local storage to persist the packing list data across browser sessions.
Handling the initial state load from local storage and ensuring that subsequent updates were correctly saved.

##### Sorting Functionality:

Implementing multiple sorting options (by input order, description, and packed status) while maintaining performance with potentially large lists.
Ensuring that the sorting logic didn't interfere with the original input order when needed.

##### User Interface and Experience:

Designing an intuitive interface that allows users to easily add, remove, and update items.
Implementing responsive design to ensure the application works well on various device sizes.

##### Form Handling:

Creating a dynamic form that allows users to input both item descriptions and quantities.
Implementing form validation to ensure that empty items aren't added to the list.

##### Performance Optimization:

Ensuring that the application remains responsive even with a large number of items in the list.
Optimising re-renders, especially when frequently updating item statuses or reordering the list.

##### Cross-browser Compatibility:

Ensuring that the application, especially the local storage functionality, works consistently across different web browsers.

##### Code Organisation:

Structuring the code into reusable components (App, Form, PackingList, Item, Stats) while maintaining clear communication between these components through props and callback functions.

These challenges were addressed through careful planning, iterative development, and thorough testing, resulting in a functional and user-friendly travel packing list application.

## Testing

### Responsive

I used <a href="http://ami.responsivedesign.is/">Am I Responsive</a> to ensure that my app worked on multiple devices.

As well as chrome developer tools, I tested for:

- Samsung Galaxy - Responsive
- Pixel 2 - Responsive
- Pixel 2 XL - Responsive
- iPhone 5s/Se/6/7/8/X - Responsive
- iPad 9.7" - Responsive
- iPad Pro - Responsive
- Surface Duo - Responsive
- Galaxy Fold - Responsive

## Credits

- React team for a great documentation.
- Jonas for his React course.

## Learning and Takeaway

- React Hooks: Utilising hooks like useState and useEffect for state management and side effects significantly simplified the code structure.
- Vercel Deployment: Learned the process of deploying a React application using Vercel, benefiting from its continuous deployment and easy integration features.

## Personal Reflections

#### Learning Experience

Developing the Far Away travel packing list application was an enriching experience that significantly enhanced my React skills. Working with hooks like useState and useEffect deepened my understanding of state management in React applications. The project also provided valuable insights into the importance of user experience design in creating intuitive interfaces.

#### Challenges and Growth

One of the most challenging aspects was implementing the sorting functionality while maintaining performance. This pushed me to think critically about data structures and algorithms, improving my problem-solving skills. Additionally, tackling responsive design across various devices broadened my CSS expertise.

#### User-Centric Approach

This project reinforced the importance of putting the user first. Features like real-time packing progress and data persistence using local storage were implemented with the user's convenience in mind. It was satisfying to create something that could genuinely make travel preparation easier for people.

#### Technical Skills Advancement

Beyond React, I gained practical experience with Vite as a build tool and Vercel for deployment. These modern development tools have expanded my toolkit for future projects. The use of local storage for data persistence was also a valuable learning experience in handling client-side data.

#### Areas for Improvement

While I'm proud of the current implementation, I see several areas for future improvements:

1. Implementing user accounts and cloud sync to make lists accessible across devices.
2. Adding categories for items to improve organisation.
3. Incorporating a drag-and-drop interface for a more interactive user experience.
4. Implementing suggested items based on destination or trip type, which would involve more complex data management and potentially integrating with external APIs.

#### Project Management Insights

This project taught me the value of scope management. Starting with a focused set of features and planning for future enhancements helped keep the project manageable while still delivering a useful product.

#### Conclusion

Overall, the Far Away project was a rewarding experience that combined technical challenges with practical utility. It has motivated me to continue exploring React's capabilities and to focus on creating applications that solve real-world problems. I look forward to applying these learnings to future projects and potentially revisiting Far Away to implement more advanced features.

## License

This project is open source and available under the [MIT License](LICENSE).

---

Happy packing and enjoy your trip! 🌴✈️🧳
