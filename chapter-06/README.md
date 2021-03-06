[![Book Cover - Advanced Platform Development with Kubernetes: Enabling Data Management, the Internet of Things, Blockchain, and Machine Learning](../img/apk8s-banner-w.jpg)](https://imti.co/kubernetes-platform-book/)

# Chapter 6: Indexing and Analytics

## Technology Reference
- [Elasticsearch]
- [Logstash]
- [Kibana]
- [Keycloak] (IAM)
- [JupyterHub]
- [Kubernetes API]

## Listings

- [Listing 6-1: Installing kernel headers and the rdb kernel module](/chapter-06/InstallingKernelHeaders.txt)
- [Listing 6-2: Development environment prerequisites](/chapter-06/DevelopmentEnvironmentPrerequisites.txt)
- [Listing 6-3: cluster-apk8s-dev4 TLS Certificate](/chapter-06/cluster-apk8s-dev4/003-data/000-namespace/05-certs.yml)
- [Listing 6-4: Elasticsearch Service](/chapter-06/cluster-apk8s-dev4/003-data/030-elasticsearch/10-service.yml)
- [Listing 6-5: Elasticsearch Statefulset](/chapter-06/cluster-apk8s-dev4/003-data/030-elasticsearch/40-statefulset.yml)
- [Listing 6-6: Logstash Service](/chapter-06/cluster-apk8s-dev4/003-data/032-logstash/10-service.yml)
- [Listing 6-7: Logstash configuration ConfigMap](/chapter-06/cluster-apk8s-dev4/003-data/032-logstash/30-configmap-config.yml)
- [Listing 6-8: Logstash pipeline configuration ConfigMap](/chapter-06/cluster-apk8s-dev4/003-data/032-logstash/30-configmap-pipeline.yml)
- [Listing 6-9: Logstash Deployment](/chapter-06/cluster-apk8s-dev4/003-data/032-logstash/40-deployment.yml)
- [Listing 6-10: Kibana Service](/chapter-06/cluster-apk8s-dev4/003-data/034-kibana/10-service.yml)
- [Listing 6-11: Kibana configuration ConfigMap](/chapter-06/cluster-apk8s-dev4/003-data/034-kibana/20-configmap.yml)
- [Listing 6-12: Kibana Deployment](/chapter-06/cluster-apk8s-dev4/003-data/034-kibana/30-deployment.yml)
- [Listing 6-13: Kibana Ingress](/chapter-06/cluster-apk8s-dev4/003-data/034-kibana/50-ingress.yml)
- [Listing 6-14: Keycloak Web Service](/chapter-06/cluster-apk8s-dev4/003-data/005-keycloak/10-service.yml)
- [Listing 6-15: Keycloak administrator and keystore credentials](/chapter-06/cluster-apk8s-dev4/003-data/005-keycloak/15-secret.yml)
- [Listing 6-16: Keycloak deployment](/chapter-06/cluster-apk8s-dev4/003-data/005-keycloak/30-deployment.yml)
- [Listing 6-17: Keycloak Ingress](/chapter-06/cluster-apk8s-dev4/003-data/005-keycloak/50-ingress.yml)
- [Listing 6-18: data-lab Namespace](/chapter-06/cluster-apk8s-dev4/005-data-lab/000-namespace/00-namespace.yml)
- [Listing 6-19: datalab ServiceAccount](/chapter-06/cluster-apk8s-dev4/005-data-lab/000-namespace/05-serviceaccount.yml)
- [Listing 6-20: datauser and hub Roles for the data-user Namespace](/chapter-06/cluster-apk8s-dev4/005-data-lab/000-namespace/07-role.yml)
- [Listing 6-21: data-user and hub RoleBindings](/chapter-06/cluster-apk8s-dev4/005-data-lab/000-namespace/08-rolebinding.yml)
- [Listing 6-22: JupyterHub Helm values](/chapter-06/cluster-apk8s-dev4/003-data/100-jupterhub/values.yml)
- [Listing 6-23: JupyterHub Ingress](/chapter-06/cluster-apk8s-dev4/003-data/100-jupterhub/50-ingress.yml)
- [Listing 6-24: Indexing and analytics development cluster configuration layout](/chapter-06/ConfigLayout.txt)

[Kibana]: https://www.elastic.co/kibana
[Elasticsearch]: https://www.elastic.co/elasticsearch/
[JupyterHub]: https://jupyter.org/hub
[Logstash]: https://www.elastic.co/logstash
[Kubernetes API]: https://kubernetes.io/docs/concepts/overview/kubernetes-api/
[Keycloak]: https://www.keycloak.org/
