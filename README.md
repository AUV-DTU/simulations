# DTU-AUV Simulations

Gz-sim based simulations for our vehicles


## Getting started

Setting the environment variable

```bash
export GZ_SIM_RESOURCE_PATH=/{path_to_this_directory}/simulations
```

Running the simulations
```bash
cd worlds
gz sim -v 4 buoyant_world.sdf
```