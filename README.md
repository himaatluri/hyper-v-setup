# K0s setup on HyperV

## Apply k0s
```
k0sctl apply -c k0s.yml
```

## Get kubeconfig
```
k0sctl kubeconfig -c k0s.yml > k0sconfig
```