# Cool Styling

## How to compile

1. **Install Sass** (if not already installed):

   ```bash
   # using npm
   npm install -g sass
   # using Homebrew
   brew install sass/sass/sass
   ```

2. **Compile SCSS to CSS**:

   ```bash
   sass src/main.scss dist/main.css
   ```

3. **Watch for changes** (optional):

   ```bash
   sass --watch scss/main.scss:css/main.css
   ```

   This will automatically recompile the SCSS files on save.
