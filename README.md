# chatbot-server

## 📋 <a name="table">Table of Contents</a>

1. ⚙️ [Tech Stack](#tech-stack)
2. 🔋 [Features](#features)
3. 🤸 [Quick Start](#quick-start)
4. 🚀 [Todo](#to-do)

## <a name="tech-stack">⚙️ Tech Stack</a>

- NodeJS
- Express

## <a name="features">🔋 Features</a>

Aı Assistant with th integration of Chat GPT. 

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)


**Cloning the Repository**

```bash
git clone https://github.com/Hnfgozel/chatbot-server.git
cd chatbot-server
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
OPENAI_API_KEY
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on these corresponding websites from [OpenAI](https://platform.openai.com/docs/quickstart?context=node)

**Running the Project**

```bash
npm run server
```

if you request with get to the http://localhost:5000 address You will receive 
{
  "message": "Hello from Server!"
}


## <a name="to-do">🚀 Todo</a>

Deploying to the Aws and manage the CI/CD process with the github Actions