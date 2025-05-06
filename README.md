npm install --save-dev backstopjs
-> For downloading the backstop

npx backstop init
-> for initialization

backstop.json
Here you add the components

npx backstop reference
-> to create the images for reference

npx backstop approve
-> if you are ok with the changes

npm run reference-and-zip
-> this is a script from package.json that run npx backstop reference and downloaded outside the project

What Does BackstopJS Do?
BackstopJS is a visual regression testing tool for web applications.
It helps you catch unwanted visual changes in your UI after code updates.

✅ What BackstopJS Actually Does:
Takes screenshots of selected web pages or UI components (your reference state).

Later, when you update your code, it takes new screenshots.

Then it compares the new screenshots with the reference ones pixel by pixel.

If there are differences, it highlights them visually and generates a browser report.

📦 Why Use BackstopJS?
To prevent visual bugs from sneaking into production.

To make sure new CSS or layout changes don't break existing designs.

Great for CI/CD pipelines, big teams, or design systems.




You can combine with storybook
