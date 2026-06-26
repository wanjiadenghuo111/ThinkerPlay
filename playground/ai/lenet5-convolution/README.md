# LeNet-5 Matrix Convolution Process

[Open experiment](./index.html) · [Back to ThinkerPlay](../../../README.md)

## Summary

This experiment visualizes matrix convolution inside the classic LeNet-5 style CNN pipeline. It helps connect the architecture diagram of a neural network with the actual numerical operations happening between layers.

## What Am I Thinking About?

CNN diagrams can look clean and simple, but each arrow hides many repeated matrix operations. By slowing the process down, this experiment turns the hidden arithmetic into a visible flow.

The useful mental model is layer-by-layer transformation: raw pixels become local responses, local responses become compact feature maps, and later stages combine those features into more abstract signals.

## How Do I Play With It?

- Follow the highlighted matrix region as convolution progresses.
- Watch how intermediate values flow into the next representation.
- Compare the input grid, kernel operation, and output feature map.
- Use available playback controls to pause, step, or replay the process.

## What Should I Observe?

- Each convolution value is produced by a repeated local calculation.
- The same kernel can generate many output positions.
- Later layers become smaller or more abstract because earlier operations reorganize the information.

## A Small Challenge

Pause on a single highlighted convolution step and try to calculate the output value manually. Does it match the visualized result?

## Files

- `index.html`: self-contained interactive demo.
- `assets/`: reserved for screenshots or preview GIFs.
