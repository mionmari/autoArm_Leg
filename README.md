# autoArm_Leg
Simple auto-rig for an IK/FK arm and reverse foot setup for legs. Undo button only "undos" the rig command if it was the last command done. 

## autoArm
Must have joints labelled shoulder, elbow, and wrist (i.e. L_Shoulder, shoulder, Rshoulder).
Select clavicle or shoulder joint and then click "rig."
Arm can be rigged as IK, FK, or with an IK/FK switch.

## autoLeg
Must have joints labelled hip, knee, and ankle (i.e. L_Hip, hip, Rhip). Foot joints must be created as if the character was standing on the XY-plane, facing in the forwards Z direction.
Select hip joint and then click "rig."
Can adjust length of foot control.
This script also creates the reverse foot joints (RevHeel, RevToe, etc.), so it is preferred to specify a custom prefix.
