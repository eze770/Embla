# EmblaV1
Extending DreamerV3 for robotic application and better Morphology awareness by implementing a FFKSM
=======
## Details
You can find a detailed description of the project under additionalMaterials/Embla.pdf.

## Usage

- install requirements (note that you need torch with cuda)
- replace pusher_v5.xml in the gymnasium lib folder (yourPythonVenv/gymnasium/envs/mujoco/assets) with the file in this repo! (necessary for the colourfilter)
- run main.py to start
- modify config to change all relevant Dreamer and FFKSM parameters

## Current state

- Core architecture done!
- Performing poorly.
- Needs adjustment or small redesign. Maybe implement SM student model.

## Acknowledgements

- [NaturalDreamer](https://github.com/InexperiencedMe/NaturalDreamer) Helped me to understand the DreamerV3 Architecture. Used the Code as a base.
- [SelfModel](https://github.com/H-Y-H-Y-H/SelfSimRobot) Original Selfmodel-code, which I modified and fused with the DreamerV3 Architecture.