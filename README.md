# :clipboard: Project.Mehrass
[in_dev :hammer_and_wrench:] This app will display a list words from the Moroccan :morocco: dialect and it's meaning, it's a dictionary like website.
With the possibility for users to join add and update more words on the fly!

Made using the MERN stack with Docker!

*MERN stands for Mongo, Express, React and NodeJS*

# :globe_with_meridians: Demo
This application is deployed and hosted on Heroku with CI/CD enabled :
[Application live demo](https://mysterious-anchorage-16443.herokuapp.com/)

# :floppy_disk: Database
MongoDB Atlas is mongoDB as a service, where the whole cluster is completely managed by mongoDB. and we can just concentrate on the application.

More information can be found here : [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

# :hash: Enviroment Variables
```
PORT=5000
NODE_ENV=production
DEBUG=false
MONGO_URI={YOUR_MONGODB_ATLAS_URI}
SECRET={YOUR_SECRET}
```

# :repeat: Developement
In the root directory run this command :

``` docker-compose -f docker-compose.dev.yml up --build ```

# :repeat_one: Production
In the root directory as well, run the following :

``` docker-compose up --build ```

# :computer: Technologies Used
* Reactjs
* Redux
* Webpack
* Axios
* Nodejs
* Express
* MongoDB
* MongoDB Atlas
* Mongoose
* Docker
* Docker Compose
* Git
* Trello
* CKEditor
* Heroku
* JWT

## :memo: License
[MIT](https://opensource.org/licenses/MIT)
