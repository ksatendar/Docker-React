D:\Docker-React> npx create-react-app client

You can now view client in the browser.

  Local:            http://localhost:3000        
  On Your Network:  http://192.168.29.8:3000     

Note that the development build is not optimized.
To create a production build, use npm run build. 
......................
install webpack dependencies:
npm install webpack webpack-cli webpack-merge webpack-dev-server html-webpack-plugin babel-loader @babel/core @babel/preset-env @babel/preset-react style-loader css-loader --save-dev

Change to "bash-bin" terminal and run the cmd below:

bin>./deploy.sh dev up
bin>./deploy.sh dev down

bin>./deploy.sh prod up
bin>./deploy.sh prod down

docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAddress}}{{end}}' <container_id>
docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAddress}}{{end}}' b184c8589b10
172.18.0.2

////////////////
Initialize a Git repository: git init 
git remote add origin https://github.com/username/repo-name.git

/////////youtube reference////////////////
/watch?v=6p7lylJEjrU&t=13s