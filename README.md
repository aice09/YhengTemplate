# My System Template

System template

## To Get Started

1. Install node modules or project dependencies

   ```
   npm install
   ```

   - In case it's a real problem, check the repository of vulnerable package for existing issues and PRs run.
     ```
     npm audit fix
     ```

2. Run Gulp to get compile Javascript, Sass, images, and dump files.

   - Build to compile all stuffs

     ```
     gulp build
     ```

   - Run this to watch your change or automatically compile your scripts

     ```
     gulp
     ```

     or use

     ```
     gulp watch
     ```

   - Run this to delete your **dist** folder.
     ```
     gulp clean
     ```

3. Install PHP packages using composer.

   - Build to compile all stuffs

     ```
     composer install
     ```

4. Rename .env.example to .env and provide your database and database credentials
5. For more info please contact me, find the following contact information inside html files of each pages.
