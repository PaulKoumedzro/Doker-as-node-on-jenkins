Setup docker as node or slave is proven to  save cost and also increase the efficiency.
In order to  create container as node, you first need to install Docker and jenkins on the same machine and then follow the steps in the setup-node.txt.
Once you done setup, go to the ipaddress:800/restart to restart the jenkins app for the changes to take effect.Accept the yes prompt allow restart.
after jenkins restart, login to jenkins and install the docker pipeline plugin and restart jenkins again.
Once you setup the node, you don't have to worry about generating keys to connect them since they are on the same machine. You can simply setup your node and build your job. 
