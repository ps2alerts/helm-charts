# helm-charts
Repo that contains the common helm charts used by the applications.

## Development

To test out the values of these charts, execute:

```shell
cd charts/microservices
helm template -f test-values.yaml . --debug
```

Update your `test-values.yaml` to suit.
