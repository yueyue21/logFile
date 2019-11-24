# To run the app:

git clone git@github.com:yueyue21/logFile.git
cd logFile

# make sure you have npm(node.js) installed
npm install

# since the nodemon is not a dependency for the project but a dev tool, if you don't have nodemon installed, run this command first
sudo npm install nodemon -g
# then
nodemon bin/www

# visit the home page at http://localhost:3000
# your log info will be generated at the same time at ./logs/app.log
# visit the logs at http://localhost:3000/logs
