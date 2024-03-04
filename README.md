
## installs
npm init -y

npm install tailwindcss postcss-cli autoprefixer

npm install live-server -g
live-server public

npx tailwindcss -o public/build/tailwind.css --watch