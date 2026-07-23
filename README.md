# 🚀 NASA Mission Control

A full-stack mission control dashboard inspired by NASA's launch management systems.
The application allows users to schedule new space launches, monitor upcoming missions, view launch history, and abort future launches through a responsive React interface backed by a RESTful Node.js API.
This project demonstrates full-stack JavaScript development, API design, database integration, testing, containerization, and production-ready deployment practices.

## 💡*Features*

- Schedule new launches
- View upcoming launches
- View launch history
- Abort scheduled launches
- RESTful API
- MongoDB database integration
- CSV data processing
- Docker support
- Automated API tests using Jest
- Responsive React frontend

## ⚙**Technologies Used**

*Backend*
- Node.js
- Express.js
- MongoDB
- Mongoose
- Jest
- Morgan
- dotenv
  
*Frontend*
- React
- JavaScript
- CSS
  
*DevOps*
- Docker
- Git
- GitHub


## 🎦**Project Structure**

- client/
- server/
- Dockerfile
- package.json


## ⚙**Installation**

</> Bash
git clone https://github.com/Chima-dan/NASA-PROJECT.git
cd NASA-PROJECT
npm install

## 🚂**Environment Variables**

*Create*
- server/.env

*Add*
</> env

MONGO_URL=your_mongodb_connection_string
PORT=8000

## ▶**Run locally**

</> Bash
npm run watch

**Frontend**
http://localhost:3000

**Backend**
http://localhost:8000/v1

## 🐳**Docker**
 *Build*
 
</> Bash
docker build -t nasa-project .

*Run*

</> Bash
docker run -p 8000:8000 --env-file server/.env nasa-project

## 📡**API Endpoints**

  Method | Endpoint         | Description                
| ------ | ---------------- | -------------------------- |
| GET    | /v1/launches     | Retrieve launches          |
| POST   | /v1/launches     | Schedule launch            |
| DELETE | /v1/launches/:id | Abort launch               |
| GET    | /v1/planets      | Retrieve habitable planets |

## 🧪**Testing**

</> Bash
npm test

## 📚**Lessons learned**

During this project I gained hands-on experience with:
- REST API development
- MongoDB Atlas
- Mongoose ODM
- Jest API testing
- Docker containerization
- Environment variable management
- Deployment preparation
- Debugging production issues

## 🚀**Future improvements**

- User authentication
- Launch notifications
- TypeScript migration
- CI/CD pipeline
- Kubernetes deployment
- AWS deployment

## 🌏**Live Demo**
*Coming soon...*

## 👨‍💻**Author**

*Amaechi Chimauche Daniel*
*GitHub*
*https://github.com/Chima-dan*
