## How to Start an Angular Project

    Install Node.js and npm
        Download and install Node.js, which includes npm.
        Verify installation:

    node -v  
    npm -v

## Install Angular CLI (Command Line Interface)

    Install globally:
```bash
    npm install -g @angular/cli
```
## Create a New Angular Project

    Create a new project (replace my-angular-app with your desired name):

    ng new my-angular-app

## Navigate to the Project Folder

    Move to your project folder:
```bash
    cd my-angular-app
```

## Run the Development Server

    Start the server:
```bash
    ng serve
```
    Access the app at http://localhost:4200/.

## Open the Project in a Code Editor

    Open the project in your preferred code editor (e.g., Visual Studio Code).

## Make Changes and Rebuild

    The development server auto-rebuilds as you make changes.

## Build for Production

    To build the app for production:

        ng build --prod

        The optimized version will be in the dist/ folder.

## Key Commands:

    Install Angular CLI: npm install -g @angular/cli
    Create Project: ng new my-angular-app
    Navigate to Folder: cd my-angular-app
    Start Development Server: ng serve
    Build for Production: ng build --prod