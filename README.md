# minimal_examples_crocoddyl
Demo scripts to quickly get started with Crocoddyl and MPC. 

An easy way to integrate this package is to clone this repository into your project and import ocp_utils and pin_utils for your use. 


# Dependencies
For OCP and MPC scripts
- [mim_robots](https://github.com/machines-in-motion/mim_robots)
- [Crocoddyl](https://github.com/loco-3d/crocoddyl) 
- [matplotlib](https://matplotlib.org/)

For visualization (optional)
- [meshcat](https://github.com/meshcat-dev/meshcat) 
- [gepetto-viewer](https://github.com/Gepetto/gepetto-viewer) 

# Usage
For the reaching task, run `python ocp_kuka_reaching.py` to solve the OCP and visualize / plot the solution. Run `python mpc_kuka_reaching.py` to simulate it in MPC in PyBullet. Same for contact task.

The scripts are minimal and self-explanatory. The machinery for data extraction and plotting is hidden in the utils. 

# Copyrights
Copyright(c) 2019-2023 New York University

# License
BSD 3-Clause License
