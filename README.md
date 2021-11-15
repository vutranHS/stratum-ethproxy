`git clone https://github.com/vutranHS/stratum-ethproxy`

To build the docker image: `docker build -t stratum-ethproxy .`

To run the docker image: `docker run -d --name my-stratum-proxy -e "REMOTE_HOST=eu1.ethermine.org" -e "REMOTE_PORT=14444" -e "REMOTE_PASSWORD=x" -p 80:2020 stratum-ethproxy`

In the example above you can point your miner to the IP address running the proxy on port 2020.
