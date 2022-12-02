# Tailwind-boilerplate

A simple boilerplate to get started on new TailwindCSS based projects. Additional plugins included in the `package.json`, yet still need to be enabled in the tailwind config file:
* `@tailwindcss/forms`
* `@tailwindcss/typography`

It also leverages the `@config` directive available since [Tailwind v3.2](https://tailwindcss.com/blog/tailwindcss-v3-2#multiple-config-files-in-one-project-using-config) to build and support multiple stylesheets

Various npm scripts have been defined to support the process
All scripts are defined in `package.json`:
* __css:global__ : generates and minifies the css file based `tailwind-global.config.js`
* __css:project__ : generates and minifies the css file based `tailwind-project.config.js`
* __build:serve__ : launches [Browsersync](https://browsersync.io/) for live reloads during the development process
* __build:run__ : runs all of the scripts mentioned above in parallel


Clone the git repository and run `npm install`