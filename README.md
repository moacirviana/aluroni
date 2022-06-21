# Anotações do curso
Usando o lint: 

### `npm init @eslint/config`

To check syntax, find problems, and eforce code style

JavaScript modules (import/export)   

React | TypeScript? Sim | Browse

Answer questions about your style

JSON | Spaces | Singles | Unix | semicolons? Y

.eslinrc.json é criado

Para os erros ’React’ must be in scope when using JSX
Add item no .eslinrc.json->Rules: "react/react-in-jsx-scope": "off",

Erros são resolvidos executando o seguinte comando:

### `npx eslint ./src --fix`

Instalando o React-Router-Dom

### `npm i react-router-dom`

### Navegação programática
import { useNavigate } from 'react-router-dom';

navigate(`/prato/${prato.id}`, {state:{...prato}}, replace:true);

O parametro replace não permite o empilhamento do history

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
