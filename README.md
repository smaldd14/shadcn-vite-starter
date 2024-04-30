# ShadCN/UI - Vite Starter
This repository provides the basic configuration for a Vite project with Shadcn/ui.

## Usage
```
npm install
npm run dev
```

### Adding ShadCN/ui components
See documentation [here](https://ui.shadcn.com/docs) for all available components. A Button has been added to `App.tsx` as an example.

# Starting a New Project with `shadcn-vite-starter`

This guide will walk you through the steps to use the `shadcn-vite-starter` repository as a starting point for a new project.

## Prerequisites

- Git
- Node.js

## Steps

1. **Clone the Repository**
   - Clone the repository and rename it to your new project name.
     ```bash
     git clone git@github.com:smaldd14/shadcn-vite-starter.git new-project-name
     ```

2. **Navigate into the Project Directory**
   - Change to your project directory.
     ```bash
     cd new-project-name
     ```

3. **Remove Existing Git History**
   - To start fresh without the original commit history, remove the `.git` directory and reinitialize it.
     ```bash
     rm -rf .git
     git init
     ```

4. **Update Remote Repository (Optional)**
   - If you wish to push to a new remote repository, set it up on GitHub, then link it.
     ```bash
     git remote add origin https://github.com/your-username/new-repository.git
     ```

5. **Customize the Project**
   - Update `package.json` and other project files to fit your new project's needs.

6. **Install Dependencies**
   - Install the necessary dependencies for your project.
     ```bash
     npm install
     ```

7. **Make Initial Commit**
   - Commit your initial project setup.
     ```bash
     git add .
     git commit -m "Initial commit for new project"
     ```

8. **Push to Remote Repository**
   - If you have set up a new repository, push your initial commit.
     ```bash
     git push -u origin master
     ```

9. **Start Development**
   - Start the development server.
     ```bash
     npm run dev
     ```

## Conclusion

Follow these steps to quickly start a new project using `shadcn-vite-starter`. This approach helps you maintain a clean slate for each new project while leveraging your existing setup.
