# schemastore

Modified JSON Schema Store to support K8s

The repository extends catalog schema from https://www.schemastore.org/ to apply k8s schema from https://github.com/yannh/kubernetes-json-schema to all files not matched in the original catalog schema.
This allows to use the single catalog for files matched by schemastore catalog (kustomization.yaml for example) and k8s resource files at the sime time.
