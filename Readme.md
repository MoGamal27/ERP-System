# ERP System

This is a comprehensive ERP (Enterprise Resource Planning) system built using Node.js and MongoDB. It includes modules for CRM, Marketing, HR, Project Management, and Support Ticketing.

## Table of Contents

- [Features](#features)
- [API Documentation](#api-documentation)
- [Folder Structure](#folder-structure)

## Features

- **CRM**: Manage customer relationships and interactions.
- **Marketing**: Track marketing campaigns and activities.
- **HR****: Manage employee data and HR processes.
- **Project Management**: Plan, track, and manage projects.
- **Support Ticketing**: Handle customer support tickets.

## API Documentation

### CRM Module

#### Get All Customers
- **URL**: `/api/crm`
- **Method**: `GET`
- **Description**: Retrieve all customers.
- **Response**: 
  ```json
  [
    {
      "_id": "60d21b8667d0d8992e610c85",
      "name": "John Doe",
      "email": "john@example.com",
      "phone": "123-456-7890",
      "company": "Example Inc.",
      "notes": "Important client",
      "createdAt": "2024-07-14T12:00:00.000Z",
      "updatedAt": "2024-07-14T12:00:00.000Z"
    }
  ]

#### Add a Customer
- **URL**: `/api/crm`
- **Method**: `POST`
- **Description**: Add a new customer.
- **Response**: 
  ```json
  [
    {
  "_id": "60d21b8667d0d8992e610c85",
  "name": "John Doe",
  "email": "john@example.com",
  "phone": "123-456-7890",
  "company": "Example Inc.",
  "notes": "Important client",
  "createdAt": "2024-07-14T12:00:00.000Z",
  "updatedAt": "2024-07-14T12:00:00.000Z"
}
  ]

  #### Marketing Module
  ## Get All Campaigns
- **URL**: `/api/marketing`
- **Method**: `GET`
- **Description**: Retrieve all marketing campaigns.
- **Response**: 
  ```json
 [
  {
    "_id": "60d21b8667d0d8992e610c86",
    "title": "Summer Sale",
    "description": "Discounts on all products",
    "startDate": "2024-07-01",
    "endDate": "2024-07-31",
    "budget": 1000,
    "createdAt": "2024-07-14T12:00:00.000Z",
    "updatedAt": "2024-07-14T12:00:00.000Z"
  }
]


  ## Add a Campaign
- **URL**: `/api/marketing`
- **Method**: `POST`
- **Description**: Add a new marketing campaign.
- **Response**: 
  ```json
 [
  {
  "_id": "60d21b8667d0d8992e610c86",
  "title": "Summer Sale",
  "description": "Discounts on all products",
  "startDate": "2024-07-01",
  "endDate": "2024-07-31",
  "budget": 1000,
  "createdAt": "2024-07-14T12:00:00.000Z",
  "updatedAt": "2024-07-14T12:00:00.000Z"
}
]

#### HR Module
  ## Get All Employess
- **URL**: `/api/hr`
- **Method**: `GET`
- **Description**: Retrieve all emplyees.
- **Response**: 
  ```json
 [
  {
    "_id": "60d21b8667d0d8992e610c87",
    "name": "Jane Smith",
    "position": "Software Engineer",
    "email": "jane@example.com",
    "phone": "123-456-7890",
    "salary": 60000,
    "hireDate": "2024-01-01",
    "createdAt": "2024-07-14T12:00:00.000Z",
    "updatedAt": "2024-07-14T12:00:00.000Z"
  }
]


## Add an Employee
- **URL**: `/api/hr`
- **Method**: `POST`
- **Description**: Add a new Employee.
- **Response**: 
  ```json
 [
  {
  "_id": "60d21b8667d0d8992e610c87",
  "name": "Jane Smith",
  "position": "Software Engineer",
  "email": "jane@example.com",
  "phone": "123-456-7890",
  "salary": 60000,
  "hireDate": "2024-01-01",
  "createdAt": "2024-07-14T12:00:00.000Z",
  "updatedAt": "2024-07-14T12:00:00.000Z"
}
]

#### Project Management Module
  ## Get All Projects
- **URL**: `/api/project-management`
- **Method**: `GET`
- **Description**: Retrieve all projects.
- **Response**: 
  ```json
 [
  {
    "_id": "60d21b8667d0d8992e610c88",
    "name": "ERP Development",
    "description": "Developing a comprehensive ERP system",
    "startDate": "2024-06-01",
    "endDate": "2024-12-31",
    "status": "In Progress",
    "createdAt": "2024-07-14T12:00:00.000Z",
    "updatedAt": "2024-07-14T12:00:00.000Z"
  }
]

 ## Add a Project
- **URL**: `/api/project-management`
- **Method**: `POST`
- **Description**: Add a new project.
- **Response**: 
  ```json
 [
  {
  "_id": "60d21b8667d0d8992e610c88",
  "name": "ERP Development",
  "description": "Developing a comprehensive ERP system",
  "startDate": "2024-06-01",
  "endDate": "2024-12-31",
  "status": "In Progress",
  "createdAt": "2024-07-14T12:00:00.000Z",
  "updatedAt": "2024-07-14T12:00:00.000Z"
}

]


#### Support Ticketing Module
  ## Get All Tickets
- **URL**: `/api/support-ticketing`
- **Method**: `GET`
- **Description**: Retrieve all support tickets.
- **Response**: 
  ```json
 [
  {
    "_id": "60d21b8667d0d8992e610c89",
    "title": "Login Issue",
    "description": "Unable to login with correct credentials",
    "status": "Open",
    "createdAt": "2024-07-14T12:00:00.000Z",
    "updatedAt": "2024-07-14T12:00:00.000Z"
  }
]


 ## Add a Ticket
- **URL**: `/api/support-ticketing`
- **Method**: `POST`
- **Description**: Add a new support ticket.
- **Response**: 
  ```json
 [
  {
  "_id": "60d21b8667d0d8992e610c89",
  "title": "Login Issue",
  "description": "Unable to login with correct credentials",
  "status": "Open",
  "createdAt": "2024-07-14T12:00:00.000Z",
  "updatedAt": "2024-07-14T12:00:00.000Z"
}
]



