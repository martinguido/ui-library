# UI Library 📚✨

Reusable, customizable UI components for responsive 📱 and accessible ♿ web design. ⚙️💻

## Features

- **Responsive Design**: Components adapt seamlessly to different screen sizes and devices.
- **Accessibility**: Built following best practices to ensure usability for all users.
- **Customizable**: Easily modify styles and behaviors to fit your project's needs.
- **Comprehensive Documentation**: Clear and detailed documentation to guide you through the integration and customization process.
- **Modern Technologies**: Utilizes the latest web technologies for optimal performance and compatibility.

## Installation

### Prerequisites

Make sure you have the following software installed:

- [Node.js](https://nodejs.org/) (LTS version recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js) or [Yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)
- [Visual Studio Code](https://code.visualstudio.com/)

### Steps

1. **Clone the repository**:

    ```bash
    git clone https://github.com/martinguido/ui-library.git
    cd ui-library
    ```

2. **Install dependencies**:

    ```bash
    npm install
    ```

    or if you prefer using Yarn:

    ```bash
    yarn install
    ```

3. **Start the development server**:

    ```bash
    npm start
    ```

    or with Yarn:

    ```bash
    yarn start
    ```

    This will start the React development server. You can view the project at `http://localhost:3000`.

4. **Run Storybook**:

    Storybook is used to develop and test UI components in isolation.

    ```bash
    npm run storybook
    ```

    or with Yarn:

    ```bash
    yarn storybook
    ```

    This will start Storybook and you can view it at `http://localhost:6006`.

## Usage

To use a component from the library in your project, follow these steps:

1. **Import the component**:

    ```javascript
    import { Button } from '@ui-library/Button';
    ```

2. **Use the component in your JSX**:

    ```jsx
    const App = () => (
      <div>
        <Button label="Click Me" />
      </div>
    );

    export default App;
    ```

## Customization

You can customize the components by modifying their styles or behaviors. Refer to the documentation for detailed customization options.

## Contributing

We welcome contributions!

## License

This project is licensed under the MIT License.
