
npm install
npm install --save-dev @vitejs/plugin-react (vite-laravel searc)
configerate vite.config.js (add react() in plugins)
configerate welcome.blade.php with(
    @viteReactRefresh
@vite('resources/js/app.js'))
npm run dev
configure .env (set http://127.0.0.1:8000 in app url)
npm run build
resource=>js=>components=>HelloReact.jsx 
app.js (import HelloReact.js)
npm install react@latest react-dom@latest
npm i -D react-router-dom@latest