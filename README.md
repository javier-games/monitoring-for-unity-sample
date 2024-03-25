# Monitoring for Unity Sample

This repository contains a sample of how to use the [Monitoring for Unity](https://github.com/javier-games/monitoring-for-unity) package.

## Features

- The [Monitoring for Unity](https://github.com/javier-games/monitoring-for-unity) package contains a native plugin for Unity using Swift for iOS to monitor CPU, GPU, and RAM usage. It includes the `StartTracking()` and `StopTracking()` methods to initiate and stop the monitoring process. Additionally, the `StopTracking()` method returns the tracked usage data in the path of the file logs.
- The General Usage Sample included in this repository contains the user interface to trigger the Plugin functionality and display the monitoring results.

![app-flow.png](Docs%2Fapp-flow.png)

## Requirements

Usage in other versions of Unity may result in unexpected behavior. Please ensure your Unity environment meets these requirements before installation to guarantee the package's optimal functionality.

- `Unity 2022.3.22f1 (LTS)`
- `Xcode 15.0.1`
- `Monitoring for Unity 0.0.0`

## Installation

You can [download](https://github.com/javier-games/monitoring-for-unity-sample/archive/refs/heads/main.zip) this repository or clone it with the following command:
```shell
git clone https://github.com/javier-games/property-refs.git
```

## Deployment

Once you have downloaded or cloned the repository, follow these steps to deploy:

1. Open Unity Hub and add the downloaded repository as a new project.
2. Ensure that the Unity environment meets the specified versions.
3. Build the project for iOS.

## License

**Monitoring for Unity Sample** is available under the CC0 1.0 Universal license. See the [LICENSE](LICENSE) file for more information. For the Monitoring for Unity package license, please refer to the [Monitoring for Unity](https://github.com/javier-games/monitoring-for-unity/blob/main/LICENSE) project repository.

## Support

For any questions or issues, please open a [new issue](https://github.com/javier-games/monitoring-for-unity-sample/issues/new) on this repository.