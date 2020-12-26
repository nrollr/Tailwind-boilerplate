# Tailwind-boilerplate
A boilerplate for frontend development based on TailwindCSS

Simple boilerplate to get started on a new TailwindCSS based project. It includes additional plugins to support TailwindUI :
* `@tailwindcss/aspect-ratio`
* `@tailwindcss/forms`
* `@tailwindcss/typography`

Various npm scripts have been defined to support the process 
All scripts are defined in `package.json`:
* __build:css__ : generates the css file with all permutations for all utilities
* __build:serve__ : launches [Browsersync](https://browsersync.io/) for live reloads during the development process
* __prod:css__ : generates a purged css file
* __prod:minify__: generates a minified version of the purged css file

Clone the git repository and run `npm install` 