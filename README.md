# graphsui

## Setup

1. We use pnpm as package manager for this project so, if you don't have it installed, follow this [guide](https://pnpm.io/installation) to do so.

2. After installing pnpm, run `pnpm install` to install the packages.

This is the tech stack used in this project:

- [Vite](https://vitejs.dev/) as our local development server
- Typescript
- React
- [Vitest](https://vitest.dev/) as the testing framework. Feel free to change to the framework of your choice.
- [Tailwind](https://tailwindcss.com/docs/installation), css framework.

Checkout the scripts in `package.json` to know how to run the application in dev mode, run tests, linter, etc.

## Project

Your assignment is to provide a UI where users can create a directed graph. The UI should allow users to:

- Create nodes
- Create edges between two nodes
- Remove nodes

Constraints:

- Assume the graph has no more than 3 components.
- Each component can have at most 8 nodes.

Additionally, provide an input field where users can specify a target node in the graph. Implement and display the execution of a
Depth-First Search (DFS) algorithm that searches the graph for the specified target node.

### Deliverables

- A functional UI for graph creation and manipulation.
- A feature to input and search for a target node using DFS, with the search process visibility demonstrated in the UI.

### Final Considerations

UI Design Flexibility: You have the freedom to design the user interface in any way you see fit.

You are required to implement the graph data structures and the Depth First Search (DFS) algorithm yourself, without using any external
libraries that provide pre-built functionalities for these tasks. This means you should write the core algorithmic code from scratch to
demonstrate understanding and capability in handling basic data structures and algorithms.
