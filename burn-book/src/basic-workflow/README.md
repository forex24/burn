# Guide

This guide will walk you through the process of creating a custom model built with Burn. We will
train a simple convolutional neural network model on the MNIST dataset and prepare it for inference.

For clarity, we sometimes omit imports in our code snippets. For more details, please refer to the
corresponding code in the `examples/guide` [directory](https://github.com/tracel-ai/burn/tree/main/examples/guide). We
reproduce this example in a step-by-step fashion, from dataset creation to modeling and training in the following
sections.
The code for this demo can be executed from Burn's base directory using the command:

```bash
cargo run --example guide
```

## Key Learnings

- Creating a project
- Creating neural network models
- Importing and preparing datasets
- Training models on data
- Choosing a backend
- Using a model for inference
