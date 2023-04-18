# <img src="https://raw.githubusercontent.com/robolaunch/trademark/main/logos/svg/rocket.svg" width="40" height="40" align="top"> robolaunch Charts

<div align="center">
  <p align="center">
    <a href="https://github.com/robolaunch/template/releases">
      <img src="https://img.shields.io/badge/release-v2.0.7-green" alt="release">
    </a>
    <a href="https://github.com/robolaunch/template/blob/main/LICENSE">
      <img src="https://img.shields.io/github/license/robolaunch/template" alt="license">
    </a>
    <a href="https://github.com/robolaunch/template/issues">
      <img src="https://img.shields.io/github/issues/robolaunch/template" alt="issues">
    </a>
  </p>
</div>

robolaunch Charts includes Helm charts for Kubernetes. Primarily aimed to provide charts for
- robolaunch Kubernetes Operators
- Marketplace Robots

## Table of Contents

- [Usage](#overview)
- [Contributing](#contributing)

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```
helm repo add robolaunch https://robolaunch.github.io/charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
<alias>` to see the charts.

For example, to install the `robot-operator` chart:

```
helm install robot-operator robolaunch/robot-operator
```

To uninstall the chart:

```
helm delete robot-operator
```

## Contributing

Please see [this guide](./CONTRIBUTING.md) if you want to contribute.
