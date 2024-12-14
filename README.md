# tftds-hw2

./main -http_port=8080 -id=0 -raft_port=5051 localhost:5052 localhost:5053

./main -http_port=8085 -id=1 -raft_port=5052 localhost:5051 localhost:5053

./main -http_port=8090 -id=2 -raft_port=5053 localhost:5051 localhost:5052