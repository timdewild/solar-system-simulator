# Solar-System-Simulator
Python module to simulate and animate the solar system in real time. An example of the animations that can be generated with the code is given below:

https://github.com/timdewild/Solar-System-Simulator/assets/93600756/b6287190-0d8b-46c2-87b6-47cd2a328b51

The notebook `example.ipynb` explains in detail how this is done. You can also download the video [here](inner_solar_system.mp4). 

## Author

Tim de Wild

## Modules required
The modules required are:
```bash
numpy
matplotlib
datetime
astropy
astroquery
```

## How to run
See the example notebook `example.ipynb`. Create a Jupyter notebook in the same directory as where `main.py` is located and import the `Body` and `SolarSystem` classes. Using these classes, the animations can be generated as explained in the example notebook.

## Integration Algorithms
The solar system is essentially an $n$-body system of point-particles that interact gravitationally according to Newton's law of gravitation. For two bodies $i$ and $j$, separated a distance $\mathbf{r}_{ij}$, it reads:


## References

- [JPL HORIZONS on-line solar system database](https://docs.astropy.org/en/stable/coordinates/solarsystem.html)
