# React and Electron Base Application
This is a base application for building desktop applications with React and Electron. It includes everything you need to start building a scalable and easy-to-maintain application.

## Installation
Before getting started, make sure you have Node.js installed on your computer. You can download it from the official [Node.js](https://nodejs.org/) website.

Once you have Node.js installed, follow these steps to get started with this application:

1.  Fork the repository or clone this repository to your computer:
```bash
git clone https://github.com/Fran-Abril/react-electron-base.git
```

2. Enter the application directory:
```bash
cd react-electron-base
```

3. Install the dependencies:
```bash
yarn install
```

## Usage
To launch the application in development mode, run the following command:

```bash
yarn electron:start
```

This will start the application and open it in an Electron window. Any changes you make to the code will automatically reload in the application window.

To build the application for production, run the following command:

```bash
yarn electron:package:{mac | win | linux}
```

This will create a compiled version of the application in the "dist" directory. The application is now ready to be distributed and used by any user.

## Project Structure
The application is structured as follows:

- `src`: This directory contains all the source code for the application.
- `public/electron.js`: This directory contains all the code related to the Electron main process.
- `public`: This directory contains all the static files for the application, such as images and style sheets.
- `package.json`: This file contains the dependencies and commands for the application.

## Contributing
If you'd like to contribute to this project, you can do the following:

1. Fork the repository.
2. Create a branch with your changes: `git checkout -b my-branch`
3. Make your changes and commit: `git commit -am 'Adding new features'`
4. Push your changes to your fork: `git push origin my-branch`
5. Create a pull request on this repository.

## License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.