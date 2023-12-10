# WoSC9-SimLess-Demo

This repository contains the setup for the [Simulate Data-Aware Serverless Workflows in Federated FaaS with SimLess](https://www.serverlesscomputing.org/wosc9/demos/d12) Demo presented at the 9th International Workshop on Serverless Computing.

To run the SimLess simulator, a Java version >= 15 needs to be installed.

Run it with the following command:

``java -jar SimLess.jar montage.yaml input.json --simulate --export --no-distribution``

## Files

All additional data that is required for the simulator is contained in the **metadata** folder.

The [montage.yaml](montage.yaml) file contains the AFCL Montage workflow.

The [input.json](input.json) file contains the input values to the workflow that are needed to simulate the workflow.