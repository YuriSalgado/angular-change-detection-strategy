# angular-performance-change-detection

Simulates counters and message pinning on signals and zoneless, practicing essential and optimizing using Angular's Change Detection Strategy

## Project Structure

```
src/app
│
├── counter/ # responsible for counter Dec/Inc and trigger binding
│ ├── counter.component.css
│ ├── counter.component.html
│ └── counter.component.ts
│
├── info-message/ # responsible for display message
│ ├── info-message.component.css
│ ├── info-message.component.html
│ └── info-message.component.ts
│
├── messages/ # responsible for container message components
│ ├── messages-list # responsible for list of message component
│   ├── messages-list.component.css
│   ├── messages-list.component.html
│   └── messages-list.component.ts
│ ├── new-message # responsible for form of new message
│   ├── new-message.component.css
│   ├── new-message.component.html
│   └── new-message.component.ts
│ ├── messages.component.css
│ ├── messages.component.html
│ ├── messages.component.ts
│ └── messages.service.ts # responsible for message add and signal handlers
│
├── app.component.html # Template that orchestrates components
├── app.component.ts # Root component logic
├── app.module.ts # Root module of Angular application
│
├── index.html # Landing page
├── main.ts # Boostrap Angular
│
└── styles.css # Global styles
```

## Installation

Use the package manager [npm](https://www.npmjs.com/) and start app

```gitbash
npm install
```

## Usage

```gitbash
npm start
```

1. Open in your browser http://localhost:4200/
2. Yellow box is a counter with one sibling component
3. Red box is a message pinning with childrens components

## License

[MIT](https://choosealicense.com/licenses/mit/)

<p align="center">
  <img src="https://i.imgur.com/dKRjpf7.png" alt="Practice - change detection - app"/>
</p>
