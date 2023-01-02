# config-server_1
MSA Side Project_1

1. DB, 
2. JWT, 
3. MS URI


1. 도커 네트워크 브릿지 설정
docker network create \
--driver=bridge \
--subnet=172.72.77.0/17 \
--ip-range=172.72.77.0/27 \
--gateway=172.72.0.1 \
msa-project

2. 
