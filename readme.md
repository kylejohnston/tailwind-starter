# Project Notes

## Tools
- CSS: [TailwindCSS](https://tailwindcss.com/)
  - [PostCSS](https://github.com/postcss/postcss)
- JS: [Alpine](https://github.com/alpinejs/alpine)

### Development
1. Run `npm install` to install dependencies
2. To start a local web server, run `npm run start`. This will watch any HTML files in the /public/ directory and refresh your browser when anything changes.
3. To compile CSS without starting a local server, run `npm run development`
4. When ready for production, run `npm run production`. PurgeCSS will remove unused Tailwind classes and cssnano will compress the output.
