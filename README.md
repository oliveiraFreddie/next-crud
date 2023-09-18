# Simple CRUD Application with Firebase

## Introduction

This project is a straightforward CRUD (Create, Read, Update, Delete) application developed using Next.js, TypeScript, Tailwind CSS, and Firebase Firestore for the database. It allows users to manage records containing names and ages. The application provides basic data management functionalities, such as adding, editing, and deleting records, and is built with modern web technologies.

![CRUD](https://github.com/oliveiraFreddie/screenshots/blob/1ffdd3936e7a0d21b4a114f8068f034e881f2273/Captura%20de%20tela%202023-09-18%20183205.png)

## Features

- Create, read, update, and delete (CRUD) operations for managing names and ages.
- Built with Next.js, TypeScript, and Tailwind CSS for a modern and responsive user interface.
- Data storage and retrieval powered by Firebase Firestore.
- Minimalistic and user-friendly design for ease of use.

## Prerequisites

Before running this project, ensure you have the following installed:

- Node.js and npm: [Download and Install Node.js](https://nodejs.org/)
- Git: [Download and Install Git](https://git-scm.com/)

## Getting Started

1. **Clone the repository:**

   ```shell
   git clone https://github.com/oliveiraFreddie/nextCrud

   ```

2. **Navigate to the project directory:**

   ```shell
   cd nextCrud

   ```

3. **Install project dependencies:**

   ```shell
   npm install

   ```

4. **Configure Firebase:**

   Create a Firebase project on the Firebase Console.
   Set up Firebase Authentication and Firestore.
   Add your Firebase configuration to the project by updating the config.ts file with your Firebase credentials.

5. **Start the development server:**

   ```shell
   npm run dev
   ```

## Usage

    Click the "Add New" button to create a new entry with a name and age.
    Existing entries are displayed in a list, and you can edit or delete them.
    All data is stored in Firebase Firestore.
    Feel free to customize and expand upon this project as needed for your own use case.
