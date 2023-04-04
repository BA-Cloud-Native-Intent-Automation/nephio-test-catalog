# test-cilium-bgp

## Description
test blueprint for cilium bgp

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] test-cilium-bgp`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree test-cilium-bgp`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init test-cilium-bgp
kpt live apply test-cilium-bgp --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
