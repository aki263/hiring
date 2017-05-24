This assignment is to set up a simple centralized logging stack in an AWS environment.

Estimated effort needed: 3-4 hours.

Requirements
============

1. A centralized logging stack with ElasticSearch as the indexing engine and Kibana as the front-end to ElasticSearch.
You are free to choose a log aggregator which suits best.

2. The logging stack should be set up in such a way that any configuration changes in ElasticSearch/Kibana/log aggregator
can be applied without any downtime.

3. For demo, deploy `this Flask app <https://github.com/gingerpayments/example-logging-app>`_ which outputs several logs to files
(access logs & application logs). The log aggregator should collect these logs.

What to deliver
===============

* Please provide a link to a Github or Bitbucket repository (or similar) so we can easily obtain and run your code.

* The repository should contain a README with instructions to set up the logging stack in an AWS account.
  Assume a newly created AWS account.

You are free to choose any automation tool, but bear in mind that we expect minimal manual steps in the instructions from
your README.
