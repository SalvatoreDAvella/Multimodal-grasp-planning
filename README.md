# Multimodal-grasp-planning

Grasping a variety of objects is still an open problem in robotics, especially for cluttered scenarios. Multimodal grasping has been recognized as a promising strategy to improve the manipulation capabilities of a robotic system. This work presents a novel grasp planning algorithm for hybrid grippers that allows for multiple grasping modalities. In particular, the planner manages two-finger grasps, single or double suction grasps, and magnetic grasps. Grasps for different modalities are geometrically computed based on the cuboid and the material properties of the objects in the clutter. The presented framework is modular and can leverage any 6D pose estimation or material segmentation network as far as they satisfy the required interface. Furthermore, the planner can be applied to any (hybrid) gripper, provided the gripper clearance, finger width, and suction diameter. 
The approach is fast and has a low computational burden, as it uses geometric computations for grasp synthesis and selection. The performance of the system has been assessed with an experimental campaign in three manipulation scenarios of increasing difficulty using the objects of the YCB dataset and the DLR hybrid-compliant gripper.

## Demonstration

The attached video for the paper submission containing some demonstrations can be found at this [link](https://alumnisssup-my.sharepoint.com/:v:/g/personal/salvatore_davella_santannapisa_it/EftsA_sm4BZGtCoJxYS4ibkBciQU978i5vEPslh3Ys_pOA?e=mndTAx).

## License
Distributed under the GNU License. See LICENSE for more information.
