# Helmify
CLI tool to convert kustomize output generated by Operator-SDK to a Helm chart.

Example:

`cat test_data/kustomize.output | go run cmd/helmify/main.go -name=test`
