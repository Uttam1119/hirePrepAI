```markdown
<<<<<<< HEAD
## 🚀 Setting Up the Project Locally

Follow these steps to get started with the project on your local machine:

### 1️⃣ Fork the Repository  
Click the **Fork** button at the top right of this repository to create your own copy.

### 2️⃣ Clone the Repository  
Clone the forked repository to your local machine:  
```sh
git clone https://github.com/your-username/repo-name.git
cd repo-name
```

### 3️⃣ Install Dependencies  
Run the following command to install the required dependencies:  
```sh
npm install
```

### 4️⃣ Start Inngest Development Server (For Inngest Functionality)  
```sh
npx inngest-cli@latest dev
```

### 5️⃣ Set Up the Database  
Run the following Prisma command to create the models in your **Neon** database:  
```sh
npx prisma migrate dev --name create-models
```

### 6️⃣ Start the Development Server  
Launch the development server with:  
```sh
npm run dev
```
=======
🚀 Setting Up the Project Locally

1️⃣ Fork the Repository  
    Click the **Fork** button at the top right of this repository to create your own copy.

2️⃣ Clone the Repository  
    Clone the forked repository to your local machine:  

    git clone https://github.com/Uttam1119/sensAI---the-Master.git
    cd sensAI---the-Master

3️⃣ Install Dependencies  
    Run the following command to install the required dependencies:  

    npm install

4️⃣ Start Inngest Development Server (For Inngest Functionality)  

    npx inngest-cli@latest dev

5️⃣ Set Up the Database  
    Run the following Prisma command to create the models in your Neon database:  

    npx prisma migrate dev --name create-models

6️⃣ Start the Development Server  
    Launch the development server with:  

    npm run dev

>>>>>>> 838a5abb9541907c0d5bd62a0d58700d9b59d65f

Now, your project should be up and running locally! 🚀  
```

### Make sure to create a `.env` file with following variables -

```
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

