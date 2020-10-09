```bash
git clone git@github.com:zhoyq/dst-dedicated-server.git
chmod -R 777 dst-dedicated-server
cd dst-dedicated-server
# 修改 DSTClusterConfig/cluster.ini
vi DSTClusterConfig/cluster.ini
cluster_name = DST Dedicated Server running on Docker :)
cluster_description = Dedicated Server running on Docker bit.ly/docker-dst
cluster_password = YouShallNotPass!!!
# 替换 DSTClusterConfig/cluster_token.txt
```