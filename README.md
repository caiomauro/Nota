# Notes Taking Desktop Application

![App Screenshot](preview.png)

This is a notes-taking desktop application written in Rust. It allows users to create, edit, and delete notes, which are saved as Markdown files (wip). The application offers both offline mode and stretch goals for online mode, enabling access to user's notes from multiple devices and collaboration on notes.

## Features

- Offline Mode (Minimum Viable Product)
  - The application is built using Tauri and Svelte to provide a lightweight and efficient desktop experience.
  - Users can create, edit, and delete notes.
  - Notes are saved as Markdown files on the user's local machine.

- Tags and Graph-like Visual Presentation
  - Users can add tags to their notes, facilitating easy categorization and organization.
  - Notes can be linked to each other, creating a graph-like visual representation.
  - This feature enables users to establish relationships between related notes for better context and understanding.

## Stretch Goals

- Online Mode with Axum and Svelte
  - Building on the MVP's offline functionality, the application will be extended to support online mode.
  - Online mode will allow users to access their notes from multiple devices, increasing accessibility and convenience.

- Collaboration on Notes
  - Users will be able to collaborate on notes in real-time, allowing multiple individuals to work together on the same note simultaneously.
  - Changes made by one user will be reflected in real-time to other collaborators, enhancing team productivity.

## How to Use

1. Clone the repository to your local machine.
2. Make sure you have Rust installed on your system.
3. Navigate to the project directory and install the required dependencies.
4. Build the application for your specific platform (Windows, macOS, Linux).
5. Run the application on your desktop.

## Getting Started with Development

To get started with development, follow these steps:

1. Install Rust and set up the development environment.
2. Clone the repository to your local machine.
3. Navigate to the project directory and install the required development dependencies.
4. Start the development server and launch the application in your browser for rapid development and testing.

## Deployment

For offline mode deployment, simply build the application for the desired platform and distribute it to users.

For online mode with Axum and Svelte, follow these steps:

1. Set up an Axum server to serve the application.
2. Set up a database to store user notes and collaborative changes.
3. Deploy the server to a hosting platform like render.com.
4. Update the application to communicate with the server for online mode.

## Contributing

We welcome contributions from the community! If you'd like to contribute to the project, please follow the guidelines outlined in CONTRIBUTING.md.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Thank you to the following open-source projects for making this application possible:

- Tauri - https://tauri.studio/
- Svelte - https://svelte.dev/
- Axum - https://axum.rs/
- Render.com - https://render.com/

Without the support of these fantastic projects, this app would not have been achievable. Thank you for your hard work and dedication to open-source software.
