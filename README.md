# Shopping List App

## Overview
The **Shopping List App** is a simple Android application built using **Jetpack Compose**. It allows users to add, edit, and delete shopping items. The app includes quantity tracking to help users organize their shopping lists more effectively.

## Features
Add new shopping items with a name and quantity.
Edit existing shopping items.
Delete shopping items from the list.
Display all shopping items in a list using `LazyColumn`.
User-friendly interface with input dialogs and basic validation.

## Technologies Used
Jetpack Compose: A modern toolkit for building native Android UI.
Kotlin: The programming language used for Android development.
State Management: Utilized to manage the list of shopping items and their editing states.

## Project Structure
ShoppingItem: A data class representing a shopping item with attributes like name, quantity, and editing state.
ShoppingListApp: The main composable function that contains the user interface, handles item addition and manages the shopping list.
ShoppingItemEditor: A composable function that provides UI for editing shopping items.
ShoppingListItem: A composable function that displays individual shopping items in the list with edit and delete buttons.

## Getting Started

### Prerequisites
Android Studio: You need Android Studio installed to run the project.
Kotlin: Make sure your project is configured to use Kotlin.

### Cloning the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/ShoppingListApp.git
