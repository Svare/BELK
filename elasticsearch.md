# Installation

+ sudo apt install gnupg -y
- wget -qO - https://artifacts.elastic.co/GPG-KEY-elasticsearch | sudo apt-key add 
* sudo apt install apt-transport-https -y
+ echo "deb https://artifacts.elastic.co/packages/7.x/apt stable main" | sudo tee -a /etc/apt/sources.list.d/elastic-7.x.list
- sudo apt update
* sudo apt install elasticsearch

# Configuration



# Reference

+ https://www.elastic.co/guide/en/elasticsearch/reference/current/install-elasticsearch.html
- https://www.elastic.co/guide/en/elasticsearch/reference/current/deb.html