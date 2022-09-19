# PyIeSOR Simulation

Python version of [iesor-physics](https://github.com/OptimusLime/iesor-physics)

## Setup

Get https://github.com/pybox2d/pybox2d

## How to use

```python
import simulator

myWorld = simulator.IESoRWorld()
myWorld.load_data_file('sampleBody224632.json')
myWorld.updateWorld(100.0)
```

## TODO

- Testing to compare with C++ results
- simple GUI to check everything is running right