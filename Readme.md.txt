To run :


make

filter = "ip"
./sniffex 0


filter = "icmp and (src host 10.0.2.5 and dst host 10.0.2.4) or (src host 10.0.2.4 and dst host 10.0.2.5)"	
./sniffex 1


filter = "tcp dst portrange 10-100"
./sniffex 2
