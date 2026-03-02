# Hello UK App (Angular)

This project was generated using the **Angular CLI (v21.1.2)** and developed as a beginner Angular application to demonstrate fundamental concepts including project structure, component modification, styling, routing setup, and production builds.

The application displays a welcome message from the UK with centered layout styling and a customized browser title.

---

## Project Objective

This repository showcases practical understanding of:

- Angular CLI project creation
- Angular application structure
- Component HTML and CSS customization
- Basic UI styling
- Development server usage
- Production build process
- Git and GitHub workflow

---

## Application Overview

The application displays:

- **Heading:** Hello from the UK!
- **Message:**  
  *"This is my Angular application, built in London."*
- Centered layout design
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

## Development Server

To start a local development server:

```bash
ng serve
````

Or automatically open the browser:

```bash
ng serve -o
```

Once running, open:

```
http://localhost:4200/
```

The application automatically reloads whenever source files are modified.

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

* Removed default Angular template
* Added container layout
* Added welcome heading and paragraph

### CSS (`app.css`)

* Background colour customization
* Centered layout using Flexbox
* Styled heading typography

### Title Update (`index.html`)

```
Hello UK | My App
```

---

## Code Scaffolding

Angular CLI provides powerful scaffolding tools.

Generate a new component:

```bash
ng generate component component-name
```

View all available generators:

```bash
ng generate --help
```

Examples include:

* components
* directives
* pipes
* services

---

## Building the Application

Create a production build:

```bash
ng build --configuration production
```

Build artifacts are generated inside:

```
dist/
```

The production build includes optimization for performance and speed.

---

## Running Unit Tests

Execute unit tests using the Vitest test runner:

```bash
ng test
```

---

## End-to-End Testing

Run e2e tests:

```bash
ng e2e
```

Angular CLI does not include an e2e framework by default; one can be added as needed.

---

## Git Workflow

The following Git commands were used to track and upload project changes to GitHub.

### Initial Project Commit

```bash
git add .
git commit -m "Create hello-uk Angular app and add welcome content"
git push origin main
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