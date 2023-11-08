
# GoodSpace-AI 
Project Link : https://goodspace-ai-frontend.vercel.app

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

# Future Improvements List
1. **User Interface Enhancements**:
  Redesign the user interface to improve usability and aesthetics.
  Implement responsive design for mobile and tablet devices.
  Add themes and customization options to cater to user preferences.

2. **Performance Optimization**:
Optimize the application for faster loading times and smoother user experiences.
 Implement caching mechanisms to reduce server load and improve response times.

3. **Security Enhancements**:
Conduct security audits and implement best practices to protect against vulnerabilities.
 Add two-factor authentication for user accounts.
 Enhance data encryption and privacy measures.

4. **Scalability**:
 Plan for increased user loads by optimizing the application's architecture.
 Implement load balancing and horizontal scaling to handle growing traffic.

5. **Integration with Third-Party Services**:
   Integrate with popular APIs, such as social media sharing, payment gateways, or mapping services.
   Offer single sign-on (SSO) options through OAuth or other authentication providers.

6. **Advanced Search and Filters**:
   Improve search functionality with advanced filters, sorting, and faceted search.
   Implement natural language processing for more intuitive search queries.

7. **Reporting and Analytics**:
   Provide detailed reporting and analytics features for users to track their data and usage.
   Create dashboards with data visualization tools to help users gain insights.

8. **Collaboration Features**:
   Enable real-time collaboration on documents or projects.
   Implement commenting and annotation features for content sharing.

9. **Automation**:
   Integrate workflow automation to reduce manual tasks and streamline processes.
   Implement chatbots or AI-driven features for customer support and user assistance.
10. **Multi-Language Support**:
     Enable users to switch between different languages or provide content in multiple languages.
    Implement internationalization and localization features.


