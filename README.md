# StackState SAP StackPack

This repository contains the StackState SAP StackPack. The code is distributed under the [Apache 2.0](LICENSE.md) license.

## Introduction

The SAP StackPack connects SAP to StackState, allowing you to monitor your SAP instance(s). You can find the
[capabilities of the StackPack](src/main/stackpack/resources/overview.md) and the [configuration instructions](src/main/stackpack/resources/detailed-overview.md) in this repository.

The SAP StackPack configures StackState to processes data produced by the SAP integration in the [StackState agent](https://github.com/StackVista/stackstate-agent). The SAP integration can be found in the [integrations repository](https://github.com/StackVista/stackstate-agent-integrations/tree/master/sap).

## Documentation

The StackState [documentation](https://docs.stackstate.com/develop/creating_stackpacks/) describes how to build and install a StackPack.

## Building

The SAP StackPack is built using the [SBT](https://www.scala-sbt.org/) tool.

In the main directory, compile the SAP StackPack using:

```
sbt compile
```

## Testing

The SAP StackPack comes with a small testing library that validates that the SAP StackPack packaging is correct.

In the main directory, test the SAP StackPack using:

```
sbt test
```

## Packaging

In the main directory, package the SAP StackPack using:

```
sbt package
```

## Versioning

The SAP StackPack release version is configured in the [version.sbt](version.sbt) file. StackPacks use [Semantic Versioning](https://semver.org/).

## Contributing

Contributions are welcome! Please check our [contribution instructions](CONTRIBUTING.md).

## Legal

Contributions to the SAP StackPack are contributed under the "inbound=outbound" principle. This means
that contributions are licensed under the same license as the [source code](LICENSE.md).
We do not require you to sign a separate CLA (Contributor License Agreement) or any other kind of document.

Thank you for your contributions!
