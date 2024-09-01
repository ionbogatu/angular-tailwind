# In a new folder initialize an empty Node folder

npm init

# In the new folder install @angular/cli

npm i @angular/cli

# In the new folder create new angular applciation

npx ng new angular-project

# Go to the newly created application

cd angular-project

Run angular applciation

npm start

Add angular material

npx ng add @angular/material

Install tailwindcss

npm install -D tailwindcss postcss autoprefixer

Initialize tailwindcss

npx tailwindcss init --ts

Import tailwind in src/styles.scss at the beginning of the file

@tailwind base;
@tailwind components;
@tailwind utilities;

Replace "content: []" on tailwind.config.ts with the following

content: ['./src/**/*.{html,ts}'],