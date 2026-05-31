# Contentways
Building open-source tools for the cloud-native ecosystem.

## Projects

### [poweradmin-go](https://github.com/Contentways/poweradmin-go)
A Go SDK for the [Poweradmin](https://www.poweradmin.org/) REST API.
```sh
go get contentways.dev/contentways/poweradmin-go
```

### [poweradmin-operator](https://github.com/Contentways/poweradmin-operator)
A Kubernetes operator for managing DNS zones and records via the Poweradmin API.
```sh
helm install poweradmin-operator oci://ghcr.io/contentways/charts/poweradmin-operator \
  --namespace poweradmin-operator \
  --create-namespace
```

## Tech Stack
Go · Kubernetes · Cloud Native · OpenSource

## Links
- 📧 [github@contentways.org](mailto:github@contentways.org)
