# docker
# 个人学习用
# nginx1.4 php redis4.0.11 mysql5.7
# 先安装docker https://docs.docker.com/install/
~~~git
git clone git@github.com:weedsks/docker.git
cd docker
cp env_example .env
sudo docker-compose up -d
~~~
切换php版本，env下修改，目前提供 5.6.37，7.1.21，7.2.9，三个版本
