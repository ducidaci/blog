# blog

 Frontend: react+redux+react-router
 
 Backend: node+express+mongoDB提供的API

### Configuration

edit mongoDb.sh, set mongodb pase

### Deploy
    git clone
    npm install
    npm install webpack babel babel-cli pm2 -g
    cd blog
    start mongo：  ./mongoDb.sh


##### Develop
    Frontend：npm run dev => localhost:7070
    Backend：npm run api


##### Production
    npm run dist(npm run dist_linux) => localhost:8080


