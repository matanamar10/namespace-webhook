# namespace-webhook
Write a webhook that is triggered when a namespace is created/updated/deleted and extracts the name of the user that made the request and logs its name. The log should be written to Elasticsearch that is deployed on the same K8S cluster (ECK) via Filebeat.
