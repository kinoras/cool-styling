# Cool Styling

## 🎨 Features

Cool Styling is my personal stylesheet designed to enhance and modernize the NTU COOL interface, making it more visually appealing.

## 🛠️ How to compile

1. **Install Sass** (if not already installed):

   ```bash
   npm install -g sass
   ```

   ```bash
   brew install sass/sass/sass
   ```

2. **Compile SCSS to CSS**:

   ```bash
   sass src/main.scss dist/main.css
   ```

3. **Watch for changes** (optional):

   ```bash
   sass --watch src/main.scss:dist/main.css
   ```

   This will automatically recompile the SCSS files on save.

## 🚀 Usage

To apply the custom styles to NTU COOL, use a browser extension (like [Stylus](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) or [User JavaScript and CSS
](https://chromewebstore.google.com/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld)) or your browser's custom CSS feature to load `dist/main.css` on COOL.

## ⚠️ Disclaimer

This project works by overriding the default styles of NTU COOL.  
**If the NTU COOL team updates their website code, some styles may break, and certain functions may even become unusable.**  
Use at your own risk.
