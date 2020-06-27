## POC TODOs
- [ ] Provision local or GKE k8s cluster
- [ ] create namespaces:
  - atom
  - ingestion
- [ ] install thanos receiver statefulset and other required k8s objects
- [ ] configure thanos recceiver to interact with gcs bucket
- [ ] configure thanos receive to behave as a cluster with replication
- [ ] configure thanos receiver for tenancy support
- [x] prepare a custom values.yaml for prometheus installation in atom namespace 
- [ ] install the prometheus to remote_write to thanos receiver
- [ ] measure the performance of write duration, query evaluation, thanos receiver space utilisation

## Creating a GKE cluster(terraform):
TODO
