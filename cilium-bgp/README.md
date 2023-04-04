# cilium-bgp

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] cilium-bgp`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree cilium-bgp`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init cilium-bgp
kpt live apply cilium-bgp --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
