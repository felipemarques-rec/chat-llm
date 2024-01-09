# Chat Application

Welcome to the Chat Application built with React.js, TypeScript, and Chakra UI!

## Table of Contents

- [Chat Application](#chat-application)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)

## Overview

This chat application is designed using React.js and TypeScript, following Clean Architecture principles. It includes a login page for user authentication before entering the chat. Chakra UI is used for styling components, providing a clean and customizable design.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/felipemarques-rec/chat-llm.git


 **## Getting Started**

**1. Navigate to the project directory:**

```bash
cd chat-application
```

**2. Install dependencies:**

```bash
npm install or yarn install
```

**## Folder Structure**

The project adheres to a Clean Architecture structure for enhanced organization and separation of concerns:

- **adapters:** External connectors and UI adaptations.
- **components:** Presentational components.
- **domain:** Houses business logic and entities.
- **features:** Contains feature-specific components, containers, services, and types.
- **interfaces:** Defines contracts and interactions.
- **pages:** Composes application pages.
- **services:** Encapsulates general services.
- **usecases:** Implements application-specific use cases.
- **utils:** Provides utility functions.

**## Configuration**

The project leverages TypeScript with path aliases for cleaner imports. Refer to `tsconfig.json` for alias configurations.

**## Usage**

**1. Start the development server:**

```bash
npm start
```

Access the application at http://localhost:3000.

**## Testing**

Execute tests using Jest:

```bash
npm test
```

**## Contributing**

Your contributions are welcome! Submit issues or pull requests to participate.

**## License**

This project is licensed under the MIT License.
