# Linkerd Tap APIServer Generator

This script uses
[APIserver Builder](https://github.com/kubernetes-incubator/apiserver-builder-alpha)
to generate an example Linkerd Tap APIServer. The Tap APIServer in the
[Linkerd repo](https://github.com/linkerd/linkerd2/) is based on this example.

## Generate example

This script generates and boots an example in
`$GOPATH/src/github.com/linkerd/linkerd2`. It expects this directory to not
exist prior to execution.

```bash
./tap-apiserver-gen
```

## Test

```bash
curl -k https://localhost:9443
```
