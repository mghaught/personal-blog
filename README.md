# personal-blog

## To run locally (at localhost:4000)

If running for the first time, first:

1. make sure Ruby is installed

2. in terminal, run: bundler install

3. run: npm install

4. run: npx tailwindcss init

OR tailwindcss command

## Start a watcher

./tailwindcss -i ./assets/css/style.css -o ./assets/dist-style.css --watch

## Compile and minify your CSS for production

./tailwindcss -i ./assets/css/style.css -o ./assets/dist-style.css --minify

If running for the second+ time:

1. run: bundler update

2. run: npm update

In all cases, after setup/updates, you need to run the following commands to get the site actually generating itself properly:

1. run:
   npx tailwindcss -i ./assets/css/style.css -o ./assets/dist-style.css --watch (this gets Tailwind actually running so that your formatting works properly)

2. run:
   jekyll serve (this hosts the site locally)

3. Launch the site
   http://127.0.0.1:4000/

## Github Pages

https://mghaught.github.io/personal-blog/
