# Convolution Kernel, Feature Map, and Pooling

[Open experiment](./index.html) · [Back to ThinkerPlay](../../../README.md)

## Summary

This experiment makes the CNN sliding-window process visible. It shows how a convolution kernel scans local regions, produces a feature map, and how pooling compresses the result.

## What Am I Thinking About?

Convolution is a way to detect local patterns with shared weights. The same small kernel is reused across different positions, so a model can notice a feature without relearning it for every location.

Pooling then trades detail for stability. It reduces spatial size while keeping the strongest or most representative signals.

## How Do I Play With It?

- Watch the kernel move across the input grid.
- Compare the selected input patch with the generated feature map value.
- Observe how pooling groups nearby activations.
- Change available controls to see how stride, kernel size, or pooling behavior affects the output.

## What Should I Observe?

- A single output cell depends only on a local input region.
- Stride changes how densely the kernel samples the input.
- Pooling can preserve strong signals while discarding exact location details.

## A Small Challenge

Find an input pattern where max pooling keeps the important signal, then find one where pooling hides a detail you care about.

## Files

- `index.html`: self-contained interactive demo.
- `assets/`: reserved for screenshots or preview GIFs.
