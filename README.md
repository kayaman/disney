# Disney

## Usage

[Helm](https://helm.sh) must be installed to use the charts. Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```sh
  helm repo add disney http://disney.magj.dev
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo
disney` to see the charts.

To install the `mickey` chart:

```sh
  helm install mickey disney/mickey
```

To uninstall the chart:

```sh
  helm uninstall mickey
```
