# doodle.new Documentation

## About doodle.new


doodle.new is an AI-powered software development tool designed for engineers and product managers to rapidly build and iterate on front-end web applications in React. It focuses on guiding users to create Minimum Viable Products (MVPs) quickly without requiring expertise in prompt engineering or front-end development.


## Getting Started

### Quick Start

Follow these steps to generate your first application with doodle.new:

1. Navigate to [doodle.new](https://doodle.new) and sign in or create an account
2. Enter your project prompt in the main prompt window
3. Watch as your React application is built in real-time
4. View your application in the preview browser
5. Use the chat interface to make changes or add features

::: tip Example Prompt
"Build me a to-do list application. It should store my to-do list items that I add to it. It should have a function to delete items and edit items, as well as a due date for each item."
:::

### System Requirements

#### Supported Tech Stack

You can build front-endReact applications with doodle.new. 
- React
- Node.js
- Packages available in NPM

## Core Features

### Generate an Application

After entering your prompt, doodle.new will:
1. Begin building your React application
2. Display the project tree as code is created
3. Run the code automatically in the preview browser

### Iterate and Improve Code

Your first application will be a simple version of what you described. You can use the chat interface to iteratively improve the code.

- Use the chat interface to make changes or add features
- doodle.new retains context of your conversation and codebase
- Changes will hot reload in the preview browser unless a full rebuild is required

### Manual edits

The code editor provides:
- Auto-complete functionality
- Undo/Redo (Command/Control + Z, Command/Control + Y)
- Auto-save functionality

## Best practices for prompting

1. Start small
   - Begin with concise, focused prompts
   - Avoid comprehensive product requirements in the first prompt
   - Make incremental changes rather than multiple changes at once

2. Stay within supported tech
   - Stick to [supported technologies](./#supported-tech-stack)
   - Focus on front-end React applications

## Technical capabilities

### What you can build
- Simple interactive front-end applications
- Client-side JavaScript applications with React
- UI using Tailwind and shadcn/ui
- Applications with state management
- Routing functionality
- Browser storage (LocalStorage, SessionStorage, IndexDB)
- API integrations using fetch or Axios

### Limitations
- No secure database for persistent storage
- No payment processing
- No user authentication
- No API key storage
- No server-side processing
- No file uploads
- No dynamic content generation on server
- May encounter CORS issues with external APIs

<!-- Coming soon:
## Deployment

### Publishing Your Project
- Deploy to JDoodle with a doodle.new URL
- Free tier includes doodle.new banner
- Premium options available for custom domains and banner-free deployment
-->

## Project Management

### Sidebar Navigation
Mouse over the left sidebar to access:
- New project creation
- Help (Community forum)
- Documentation
- Pricing
- Logout
- Credit limit display
- Username and plan information

## Troubleshooting

### Error Resolution
If you encounter errors:
1. Check the preview browser for error messages
2. Copy the error message
3. Paste it into the chat window
4. doodle.new will attempt to fix the error automatically

Still having trouble? Reach out to us on [Community](https://community.jdoodle.com/).

### Usage Restrictions
- Prompts for unsupported tech stack may be declined
- Unsafe or illegal prompts will be rejected
- [Terms of service](https://doodle.new/terms) violations may result in account suspension

## Coming Soon
- GitHub integration for project export and deployment
- Deploy your application with a doodle.new URL
- Deploy to your own custom domain
