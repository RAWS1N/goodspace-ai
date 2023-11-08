
# GoodSpace-AI

A chatbot powered by OpenAI allows users to engage in natural and interactive conversations by asking questions and seeking information or assistance. Leveraging the capabilities of OpenAI, this chatbot can provide relevant and accurate responses to a wide range of inquiries. Whether you need information on a specific topic, assistance with tasks, or simply want to engage in a friendly conversation, this chatbot is designed to provide timely and helpful answers, enhancing user experiences and making it a versatile and user-friendly tool for information retrieval and engagement.
# Local Setup

## Environment variables
### Backend
```python
#local mongodb setup, we can provide mongodb atlas link also
MONGO_URI=mongodb://127.0.0.1:27017
#database name can be anything
DATABASE="goodspace-ai"
#openAI api key
OPENAI_API_KEY=""
#frontend url to allow client request by cors
FRONTEND_URL="http://localhost:5173"

PORT = 5000

JWT_SECRET="my_secret"
```

### Frontend
```python 
#Local backend url
VITE_BASE_URL="http://localhost:5000"
```

## Installation

### Backend
```python
#navigate to root folder
cd goodspace-ai
#navigate to backend folder
cd backend
# create .env file 
#Install the required libraries and packages dependencies:
npm i 
# Run the development server:
 npm run dev
 or 
 # Run the production server:
 npm start
```

### Frontend

```python
#navigate to root folder
cd goodspace-ai
#navigate to frontend folder
cd frontend
# create .env.local file 
#Install the required libraries and packages dependencies:
npm i 
# Run the development server:
 npm run dev
```

# Technology
RecipeApp uses a number of open source projects to work properly:
- [Vite] - React enhanced for web apps!
- [TailwindCSS] - CSS enhanced for web apps!
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]

