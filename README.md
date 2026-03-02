# Hello UK App (Angular)

A simple Angular application created using the Angular CLI to demonstrate basic project structure, component editing, styling, routing setup, and production building.

The application displays a welcome message from the UK with centered layout styling and a customized browser title.

---

## Project Objective

This project was built to practice and demonstrate:

- Creating an Angular application using Angular CLI
- Understanding Angular project structure
- Editing component HTML and CSS
- Applying page styling and layout techniques
- Running a development server
- Creating a production build
- Using Git and GitHub for version control

---

## Application Overview

The application displays:

- **Heading:** Hello from the UK!
- **Message:**  
  *"This is My Name's Angular application, built in London."*
- Centered page layout
- Light blue background styling
- Custom browser tab title

---

## Technologies Used

- Angular
- TypeScript
- HTML5
- CSS3
- Angular CLI
- Node.js
- Git & GitHub

---

## Project Setup

### 1. Clone the Repository

```bash
git clone https://github.com/cherryaugusta/hello-uk.git
cd hello-uk
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Run Development Server

```bash
ng serve -o
```

The application will open automatically at:

```
http://localhost:4200/
```

---

## Project Structure (Key Files)

```
src/
│
├── app/
│   ├── app.html        # Main component template
│   ├── app.css         # Component styling
│   └── app.ts          # Component logic
│
├── index.html          # Application entry HTML
└── styles.css          # Global styles
```

---

## Implemented Changes

### HTML (`app.html`)

* Removed default Angular template content
* Added container layout
* Added welcome heading and descriptive paragraph

### CSS (`app.css`)

* Changed page background colour
* Centered content vertically and horizontally
* Styled heading font size and colour

### Title Update (`index.html`)

```
Hello UK | My Name's App
```

---

## Development Commands

### Start Development Server

```bash
ng serve
```

### Start and Open Browser Automatically

```bash
ng serve -o
```

### Create Production Build

```bash
ng build --configuration production
```

Production-ready files are generated inside:

```
dist/
```

---

## Initial Project Commit

```bash
git add .
git commit -m "Create hello-uk Angular app and add welcome content"
```

---

## Learning Outcomes

* Understanding Angular CLI workflow
* Editing Angular components
* Applying CSS styling in Angular applications
* Managing version control using Git
* Creating optimized production builds

---

## Disclaimer

This repository is created **strictly for educational purposes and skills demonstration only**.
It serves as a learning exercise and portfolio showcase. The application is not intended for commercial use or production deployment.

---
