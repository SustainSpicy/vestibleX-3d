# Textile-customizer by OYELEKE ISREAL TIMILEHIN

- [Description](#Description)
- [Key Features](#key-features)
- [Technologies used](#technologies-used)
- [Configuration and Setup](#configuration-and-setup)
- [Usage](#Usage)

## Description

The Customizer is a web application designed for users to create custom shirt designs using a 3D customization tool. With several customization options, including color, file upload, and AI-generated designs, users can create unique and exclusive designs that fit their personal style.

The project consists of two main components: the Home page and the Customizer page. The Home page provides an introduction to the project and allows users to begin the custom design process. The Customizer page is where users can customize their shirt designs.

The Customizer is built using React, Framer Motion, Valtio, Node.js, Express, and the DALL-E API.

## Key Features

- 3D customization tool
- Multiple customization options
- Logo and stylish shirt filter tabs
- Responsive design

## Technologies used

The Customizer is built using the following technologies:

- React
- Framer Motion
- Valtio
- React-color
- React-three fiber
- React-three dreir
- Tailwindcss
- Node.js
- Express
- DALL-E API

## Configuration and Setup

In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine.

- Open the project in your prefered code editor.
- Go to terminal -> New terminal (If you are using VS code)

```
$ cd client
$ npm install or yarn install (to install client-side dependencies)
$ npm run dev (to start the client)
```

Note: You will also need to set up a local DALL-E API server to use the AI-generated designs tab.

```
$ cd server
$ npm install or yarn install (to install server-side dependencies)
$ npm start (to start the server)
```

## Usage

To use the Customizer, follow these steps:

1. Navigate to `http://localhost:5173` in your web browser.
2. Click the "Customize It" button to begin customizing your shirt design.
3. Use the tabs to select different customization options, including color, file upload, and AI-generated designs.
4. Choose from different filter tabs to switch between logo and stylish shirt designs.
5. Download your custom design as an image.

## Contributing

Contributions to the Customizer are welcome. If you find a bug or have a feature request, please open an issue or submit a pull request.

## License

The Customizer is licensed under the MIT License.
