# components-kserve

## Purpose

This component enables distributed workloads in the DataScienceCluster for llmd.


## Usage

This component can be added to a base by adding the `components` section to your overlay `kustomization.yaml` file:

```yaml
apiVersion: kustomize.config.k8s.io/v1beta1
kind: Kustomization

resources:
  - ../../base

components:
  - ../../components/components-distributed-workloads
```
