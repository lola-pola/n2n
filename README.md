# n2n
n2n

![server client](images/n2n_com.png)
![client client ](images/n2n_network.png)



## deploy server 
"""" 
kubectl apply -f n2n-server.yaml
""""
go to server and start the server 
supernode -l 1024 -f  




## deploy client

'''
kubectl apply -f n2n.yaml
'''

start the client on each 
edge -d n2n0 -a 10.9.9.1 -c mypbxnet -k mypass -l <supernode_host>:<port>