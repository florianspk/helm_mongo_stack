# Helm Chart for MongoDB with MongoDB Express

This Helm Chart enables you to quickly deploy MongoDB using the official Bitnami MongoDB chart, while also providing the option to include MongoDB Express for a graphical user interface.

## Prerequisites

    Kubernetes 1.12+
    Helm 3.0+

## Installation

To install this chart, use the following command:

```bash
helm install mongodb-stack --values quick-values.yaml . -n mongodb --create-namespace
```

This command deploys MongoDB with MongoDB Express using the values defined in quick-values.yaml. Make sure to customize the values according to your requirements.
Customization

You can customize the deployment by modifying the values in the values.yaml file. You can also create your own values file and pass it during installation.

## Directory Structure

    charts/: Directory containing chart dependencies.
    templates/: Contains the YAML templates used to generate Kubernetes manifests.
    values.yaml: File containing default values for the chart.
    quick-values.yaml: Preconfigured values file for quick installation.

## Configuration

The main configuration options are listed in the values.yaml file. Refer to this file to customize your deployment.
Contributing

Contributions are welcome! If you'd like to improve this chart, please submit a pull request.

## License

This chart is distributed under the GNU General Public License Version 3