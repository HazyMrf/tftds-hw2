# tftds-hw2

./raft -http_port=8080 -id=0 -raft_port=7051 localhost:7052 localhost:7053

./raft -http_port=8085 -id=1 -raft_port=7052 localhost:7051 localhost:7053

./raft -http_port=8090 -id=2 -raft_port=7053 localhost:7051 localhost:7052