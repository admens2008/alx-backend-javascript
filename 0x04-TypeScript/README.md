
0x04. TypeScript Project (ALX)
Project Overview
This project covers various TypeScript tasks aimed at enhancing your understanding of TypeScript basics, interfaces, classes, functions, DOM manipulation, generic types, namespaces, declaration merging, and nominal typing. Each task is structured to progressively build your TypeScript skills.

Learning Objectives
By the end of this project, you will be able to explain and implement the following concepts:

Basic types in TypeScript
Interfaces, Classes, and functions
Working with the DOM and TypeScript
Generic types
Using namespaces
Merging declarations
Using an ambient Namespace to import an external library
Basic nominal typing with TypeScript

Project Structure
The project is organized into multiple tasks, each located in its own directory. Configuration files required for each task are provided and must be used as specified.

Task 0: Creating an Interface for a Student
Directory: task_0
Files: package.json, .eslintrc.js, tsconfig.json, webpack.config.js, js/main.ts
Description: Define a Student interface, create student objects, and render them in an HTML table using Vanilla JavaScript.

Task 1: Let's Build a Teacher Interface
Directory: task_1
Files: package.json, tsconfig.json, webpack.config.js, js/main.ts
Description: Define a Teacher interface with modifiable and optional attributes. Extend this interface to create a Directors interface.

Task 2: Extending the Teacher Class
Directory: task_1
Files: js/main.ts
Description: Extend the Teacher interface to include Directors interface with additional attributes.

Task 3: Printing Teachers
Directory: task_1
Files: js/main.ts
Description: Write a printTeacher function and its interface to format teacher names.

Task 4: Writing a Class
Directory: task_1
Files: js/main.ts
Description: Define a StudentClass with specific methods and interfaces for its constructor and class.

Task 5: Advanced Types Part 1
Directory: task_2
Files: package.json, tsconfig.json, webpack.config.js, js/main.ts
Description: Create DirectorInterface and TeacherInterface with specified methods. Implement classes for Director and Teacher.

Task 6: Creating Functions Specific to Employees
Directory: task_2
Files: js/main.ts
Description: Implement isDirector type predicate and executeWork function to call specific methods based on employee type.

Task 7: String Literal Types
Directory: task_2
Files: js/main.ts
Description: Define a string literal type Subjects and implement the teachClass function.

Task 8: Ambient Namespaces
Directory: task_3
Files: package.json, tsconfig.json, webpack.config.js, js/interface.ts, js/crud.d.ts, js/main.ts
Description: Create types and interfaces, and utilize an external crud.js library with ambient declarations.

Task 9: Namespace & Declaration Merging
Directory: task_4
Files: package.json, tsconfig.json, js/subjects/Cpp.ts, js/subjects/Java.ts, js/subjects/React.ts, js/subjects/Subject.ts, js/subjects/Teacher.ts, js/main.ts
Description: Implement a Subjects namespace with classes for different subjects and merge declarations.

Task 10: Update task_4/js/main.ts
Directory: task_4
Files: js/main.ts
Description: Export constants and log subject details using the methods defined in the Subjects namespace.

Task 11: Brand Convention & Nominal Typing
Directory: task_5
Files: package.json, tsconfig.json, webpack.config.js, js/main.ts
Description: Define MajorCredits and MinorCredits interfaces with branding properties and implement functions to sum credits.

Requirements
Use allowed editors: vi, vim, emacs, Visual Studio Code
All files should end with a new line
Transpile files on Ubuntu 18.04
Use TypeScript extensions .ts for scripts
No TypeScript compilation errors or warnings
Include a README.md file in the root directory of the project.

Usage
Clone the repository:

git clone https://https://github.com/admens2008/alx-backend-javascript.git

Navigate to the project directory:

cd alx-backend-javascript/0x04-TypeScript

Install dependencies:
npm install

Build the project:
npm run build

Run the project:
npm start

Manual QA Review
Ensure that all tasks are completed as specified.
Verify that the TypeScript compiler does not show any warnings or errors.
Test the functionality of each task to ensure correctness.
Request a manual QA review once you are done with the project.
