# Welcome to Elastic-Agent 7.17.1

Agent manages other beats based on configuration provided.

## Getting Started

To get started with Elastic-Agent, you need to set up Elasticsearch on
your localhost first. After that, start Elastic-Agent with:

     ./elastic-agent -c elastic-agent.yml -e

This will start Elastic-Agent and send the data to your Elasticsearch
instance. To load the dashboards for Elastic-Agent into Kibana, run:

    ./elastic-agent setup -e

For further steps visit the
[Quick start](https://www.elastic.co/guide/en/beats/elastic-agent/7.17/elastic-agent-installation-configuration.html) guide.

## Documentation

Visit [Elastic.co Docs](https://www.elastic.co/guide/en/beats/elastic-agent/7.17/index.html)
for the full Elastic-Agent documentation.

## Release notes

https://www.elastic.co/guide/en/beats/libbeat/7.17/release-notes-7.17.1.html
