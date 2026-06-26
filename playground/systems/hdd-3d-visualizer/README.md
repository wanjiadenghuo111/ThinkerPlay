# HDD 3D Visualizer

[Open experiment](./index.html) · [Back to ThinkerPlay](../../../README.md)

## Summary

This experiment presents a hard disk drive as an inspectable 3D system. It makes the physical relationship between platter, spindle, actuator, and read-write head easier to reason about.

## What Am I Thinking About?

Storage is often described as an abstract capacity number, but mechanical drives are physical systems with moving parts, timing constraints, and spatial layout. Seeing those parts together makes performance and failure modes easier to discuss.

The core idea is systems thinking: behavior emerges from the coordination of components, not from one isolated part.

## How Do I Play With It?

- Inspect the 3D model from different angles.
- Use available controls to view or animate HDD components.
- Watch the relationship between platter motion and head positioning.
- Open the log view when you want to inspect runtime events.

## What Should I Observe?

- The platter and actuator solve different parts of the access problem.
- Movement and position matter as much as stored data.
- A hardware system can be understood as geometry plus timing plus control.

## A Small Challenge

Try to explain why random access is mechanically different from sequential access using only what you can observe in the visualization.

## Files

- `index.html`: self-contained interactive demo.
- `assets/`: reserved for screenshots or preview GIFs.
