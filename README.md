# builder-templates
云原生构建器模板库

### 打包模板

```
helm package ./stores/builtin/
```

### 推送模板到OCIRegistry

```
helm push builtin-0.1.0.tgz  --insecure-skip-tls-verify  oci://hub.cloud.lingbohome.com/shipper/template-store
```