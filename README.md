# Travel Packing List App

## Overview

The Travel Packing List App is a React application designed to help users create and manage a packing list for their trips. The app includes features such as adding items, marking items as packed, sorting the list, and displaying statistics. This project showcases various key React concepts, including state management, components, props, conditional rendering, and event handling.

## Components

### 1. `App`

- The main component responsible for rendering the entire application.
- Manages the state of the packing list items using the `useState` hook.
- Includes sub-components such as `Logo`, `Form`, `PackingList`, and `Stats`.

### 2. `Logo`

- A simple component displaying the logo for the packing list app.

### 3. `Form`

- A form component allowing users to add new items to the packing list.
- Uses the `useState` hook to manage the state of form inputs.

### 4. `PackingList`

- A component responsible for displaying the list of packing items.
- Allows users to delete items, toggle their packed status, clear the entire list, and sort the list based on different criteria.

### 5. `Item`

- Represents an individual item in the packing list.
- Allows users to mark the item as packed, delete the item, and displays the quantity and description.

### 6. `Stats`

- Displays statistical information about the packing list, including the total number of items, the number of packed items, and the packing percentage.

## Usage

1. Open the app in your browser.
2. Use the form to add items to your packing list.
3. Manage your packing list by marking items as packed, deleting items, and sorting the list.
4. View statistical information about your packing progress in the footer.

## Running the Application

1. Clone the repository:

    ```bash
    git clone https://github.com/Olusegun-Light/Travel-Packing-List-App
    cd Travel-Packing-List-App
    ```
2. Install dependencies:

    ```bash
    npm install
    ```

3. Start the development server:

    ```bash
    npm start
    ```