# README

Steps to generate this app:

 - Generate app `rails new --skip-sprockets -J --skip-turbolinks demo-project`
 - Add `gem 'webpacker', '6.0.0.rc.5'
gem 'react_on_rails', git: 'https://github.com/gscarv13/react_on_rails.git'` to the gem file

- On the terminal:
```bash
 bundle
 bundle exec rails webpacker:install
 git add .
 git commit -m "Initial commit"
 rails generate react_on_rails:install
```
- To run the server `foreman start -f Procfile.dev`
- visit `http://localhost:3000/hello_world`