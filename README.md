ELK Stack Eval
==============

Steps
-----
First off clone this repo then cd into the project directory then run the following commands:

    wget https://download.elasticsearch.org/elasticsearch/elasticsearch/elasticsearch-1.1.1.deb
    wget https://download.elasticsearch.org/logstash/logstash/packages/debian/logstash_1.4.0-1-c82dc09_all.deb
    wget https://download.elasticsearch.org/kibana/kibana/kibana-3.0.1.tar.gz
    git submodule update --init
    vagrant up
    x-www-browser http://localhost:8080/kibana
    x-www-browser http://localhost:8080/elasticsearch-head

References
----------

* http://cookbook.logstash.net/recipes/rsyslog-agent/
* https://medium.com/what-i-learned-building/e855bc08975d
