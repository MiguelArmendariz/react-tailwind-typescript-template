# react-tailwind-typescript-template
This project is a basic template for a react application using webpack, and
YARN as package manager.

## Content
* Webpack configuration for local and prebuild.
* Public folder like create-react-app.
* Src folder without file structuring.
* Typescript support.
* Eslint with basic configuration **using Wesbos** for typescript. **Read important Notes**
* The template works with both css and scss, but is highly recommended to use tailwind.
* MIT license.

#### Important Notes

When you run yarn first and start the project you should see some headers but **without** styles,
they should look identical.

**Tailwind CSS** 
Please update the **content** array with your files pattern. Check docs to update them properly.
https://tailwindcss.com/docs/content-configuration

**THIS NEEDS NODE 12.13.0**

#### Recommendations

To update packages based in package.json range you can use **yarn upgrade-interactive** which will allow you to select which packages to update.

Otherwise if you want to update to latest, ignoring range, you can use **yarn upgrade-interactive --latest**.

Feel free to contact me if you have suggestions/requests.
