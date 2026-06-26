# Angular Movie CRUD Application

A Movie Management application built with Angular that demonstrates CRUD (Create, Read, Update, Delete) operations using RESTful APIs. The project showcases Angular services, HttpClient, component-based architecture, and frontend-backend integration.

---

## Features

* Display movie list
* Retrieve movie details by ID
* Add new movies
* Update existing movies
* Delete movies
* REST API integration using Angular HttpClient
* Modular Angular architecture

---

## Tech Stack

### Frontend

* Angular
* TypeScript
* HTML5
* CSS3

### Backend Communication

* Angular HttpClient
* REST APIs

---

## Project Structure

```
src/
├── app/
│   ├── components/
│   ├── services/
│   ├── models/
│   ├── app-routing.module.ts
│   └── app.module.ts
```

---

## Running the Project

Clone the repository

```bash
git clone https://github.com/<your-username>/angular-movie-crud.git
```

Install dependencies

```bash
npm install
```

Start the Angular development server

```bash
ng serve
```

Open

```
http://localhost:4200
```

---

## Backend Configuration

The application currently communicates with a backend running locally:

```
http://localhost:8080/api/
```

Example endpoints:

* GET `/movies`
* GET `/movies/{id}`
* POST `/movies`
* PUT `/movies/{id}`
* DELETE `/movies/{id}`

---

## Concepts Demonstrated

* Angular Services
* Dependency Injection
* HttpClient
* Observables
* Component-based Design
* RESTful API Communication
* CRUD Operations

---

## Future Improvements

* Authentication
* Search and filtering
* Pagination
* Reactive Forms validation
* Unit testing
* Docker deployment
* Responsive UI enhancements
