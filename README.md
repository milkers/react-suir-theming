# Create React App with SUIR Theming

This project was bootstrapped with;
- [Create React App](https://github.com/facebook/create-react-app).
- [Semantic UI React - SUIR](https://react.semantic-ui.com/)


After you run `npm i`, you can start the project with `npm start`. It runs on port `http://localhost:3010`.

Themes are under `src/semantic-ui` folder.
`theme.config` file manages what theme to load.

Initially it is loading default themes, with styles overriden by variables under `mysite` folder.

You can check semantic-ui's default style variables under `src/semantic-ui/themes/default` folder. This folder is read only, please do not make any updates to the `themes` folder and files it contains.

Let's say you want to change the button styles. Look for the default button variables under `src/semantic-ui/themes/default/elements/button.variables` to see what values you can change in your `mysite` folder. Then go to `src/semantic-ui/mysite/elements/buttons.variables` file (You can add `.less` extension to that file's name for code highlighting if it is not already done). Then you can give new values to the variables in that file under the `mysite` folder.