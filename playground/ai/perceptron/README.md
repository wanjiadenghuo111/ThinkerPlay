# Perceptron Training Process

[Open experiment](./index.html) · [Back to ThinkerPlay](../../../README.md)

## Summary

This experiment visualizes how a perceptron learns a linear decision boundary from labeled points. Instead of treating training as a black box, it shows the relationship between mistakes, weight updates, and the moving separator line.

## What Am I Thinking About?

A perceptron is a small but important model: it learns by being wrong. Each misclassified point pushes the boundary in a direction that makes the same mistake less likely next time.

The key idea is not just classification, but correction. The model has no deep memory or hidden strategy; its behavior comes from repeated local updates.

## How Do I Play With It?

- Add or inspect points on the classification canvas.
- Start or step through training.
- Adjust parameters such as learning behavior when available.
- Watch the decision boundary change after errors.

## What Should I Observe?

- Linearly separable data should eventually produce a stable boundary.
- Harder point layouts create more boundary movement.
- The order of examples can change the path of training, even when the final result is similar.

## A Small Challenge

Create a point layout that looks almost separable but causes the boundary to keep moving for a long time. What kind of point causes the model the most trouble?

## Files

- `index.html`: self-contained interactive demo.
- `assets/`: reserved for screenshots or preview GIFs.
