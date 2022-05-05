Run `npm install` after cloning the project.

Install (https://www.vultr.com/docs/install-apache-kafka-on-ubuntu-20-04) and run kafka `sudo systemctl enable --now kafka.service` and zookeeper `sudo systemctl enable --now zookeeper.service`

Check status `sudo systemctl status kafka zookeeper`

Install and start mongo db: `sudo apt install mongodb-org`, `sudo systemctl start mongod`,`sudo systemctl enable mongod`,`mongo --eval 'db.runCommand({ connectionStatus: 1 })'`

Run `node app.js` to run the project.

Add the orders on `http://localhost:8080/create` by POST request with params
