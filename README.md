# Foundit_main

## Install Dependencies
1.Run the following command to install all the required npm packages: npm install

2.Start the Development Server
To start the development server use: npx webpack serve --config webpack.dev.js


## Troubleshooting
If the above command doesn't work follow these steps

Check Webpack Installation

Verify if Webpack is installed by running: npm list webpack

Install Webpack

If Webpack is not installed, install it locally using: npm install webpack webpack-cli --save-dev


## Common Issues
Command Not Found: If you encounter a zsh: command not found: webpack error, ensure your node_modules/.bin directory is in your PATH.

1.Add this to your .zshrc or .bashrc file: export PATH="./node_modules/.bin:$PATH"

2.Reload your shell: source ~/.zshrc

3.Vulnerabilities: If npm reports vulnerabilities, fix them by running: npm audit fix


## Additional Commands
1.To list installed Webpack versions: list webpack

2.To install Webpack globally (optional): npm install -g webpack webpack-cli

## Notes
Ensure you have Node.js and npm installed on your system You can check your versions with:

node -v

npm -v


## Thank You....
