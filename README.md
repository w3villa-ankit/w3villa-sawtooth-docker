# w3villa-sawtooth-docker
## sawtooth 4 node setup
### install docker and docker-compose on all nodes
    ### Importent Ports 8800 4004 8008 80 443
    ## Node1 master node
        #### git clone https://github.com/w3villa-ankit/w3villa-sawtooth-docker.git
        #### sudo docker-compose -f sawtooth-master.yaml up -d
        #### curl http://nodeip:8008/blocks
    ## node2 worker node 
        #### git clone https://github.com/w3villa-ankit/w3villa-sawtooth-docker.git
        #### sudo docker-compose -f sawtooth-node2.yaml up -d
        #### curl http://node2ip:8008/blocks
    ## node3 worker node 
        #### git clone https://github.com/w3villa-ankit/w3villa-sawtooth-docker.git
        #### sudo docker-compose -f sawtooth-node3.yaml up -d
        #### curl http://node3ip:8008/blocks

    ## node4 worker node 
        #### git clone https://github.com/w3villa-ankit/w3villa-sawtooth-docker.git
        #### sudo docker-compose -f sawtooth-node4.yaml up -d
        #### curl http://node4ip:8008/blocks        