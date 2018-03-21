## Get Started

1. **Initial Machine Setup**. First time running the starter kit? Then complete the [Initial Machine Setup]().
2. **Clone the project**.  `git clone http://pasi.jncb.com/kratos/ncb-mobile-app.git`.
3. **Run the setup script**. `npm run install`
4. **Run the example app**. `npm start`
This will run the automated build process, start up a webserver, and open the application in your default browser. When doing development with this kit, this command will continue watching all your files. Every time you hit save the code is rebuilt, linting runs, and tests run automatically.
5. **Having issues?** See "Having Issues?" below.

## Initial Machine Setup

1. **Install [Node 8.10.0 or greater](https://nodejs.org)** Need to run multiple versions of Node? Use [nvm](https://github.com/creationix/nvm).
2. **Install [Git](https://git-scm.com/downloads)**.
3. **Install [Atom](https://atom.io)**. Install the following plugins from the Settings page, under the Packages section:
   - **editorconfig**, help maintain consistent coding styles between different editors
   - **emmet**, web development related autocompletions
   - **language-javascript-jsx**, code highlighting for JSX
   - **linter**, support generic linting, requires specific linter plugin
   - **linter-eslint**, specific plugin for eslint, a javascript linter
   - **linter-ui-default**, ui for the linter package
   - **react** react language, indentation and autocomplete support
4. Add **[SSH credentials](https://docs.gitlab.com/ce/ssh/README.html)** to your Gitlab profile
4. On a Mac? You're all set. If you're on Linux or Windows, complete the steps for your OS below.

**On Windows:**

* **Install [Python 2.7](https://www.python.org/downloads/)**. Some node modules may rely on node-gyp, which requires Python on Windows.
* **Install C++ Compiler**. Browser-sync requires a C++ compiler on Windows. [Visual Studio Express](https://www.visualstudio.com/en-US/products/visual-studio-express-vs) comes bundled with a free C++ compiler. Or, if you already have Visual Studio installed: Open Visual Studio and go to File -> New -> Project -> Visual C++ -> Install Visual C++ Tools for Windows Desktop. The C++ compiler is used to compile browser-sync (and perhaps other Node modules).

## Having Issues? Try these things first.
1. Make sure you ran all steps in [Get started](#get-started) including the [initial machine setup](#initial-machine-setup).
2. Run `npm install` - If you forget to do this, you'll see this: `babel-node: command not found`.
