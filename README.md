logstash-wowza
==============

Description
-----------

We are using nxlog as shipper (http://nxlog.org/) and not logstash.
Our logstash is for our gateway to ElasticSearch. We don't use middleware as redis at the moment. With this regexp line is enough to parse the lines and it is working perfectly.

We are using numerical types to get numerical operations later. For example: using kibana.

Environment
-----------

I am using this config file with:

* CentOS 6.5
* logstash 1.4.1-1
* ElasticSearch 1.1.2-1

