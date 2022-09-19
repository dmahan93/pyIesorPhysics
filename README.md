# PyIeSOR Simulation

Python version of [iesor-physics](https://github.com/OptimusLime/iesor-physics)

## Setup

Get https://github.com/pybox2d/pybox2d

Also if you want to view what's happening from a specific json,

```bash
pip install -r requirements_test.txt
```

## How to use

```python
import simulator

myWorld = simulator.IESoRWorld()
myWorld.load_data_file('sampleBody224632.json')
myWorld.updateWorld(100.0)
```

to simulate your world.

if you want to view it:
```bash
python -m framework_simulator
```

## TODO

- Testing to compare with C++ results