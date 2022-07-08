# QuestObjectTracker
Tracking external Objects just with your Oculus Quest or Quest 2 and your Android Phone. There's always been the problem of tracking external/real-world-objects standalone on Oculus Quest or Quest 2. I now solved this with QuestObjectTracker.

# How it works
There are basically two variants of QuestObject Tracker:

# 1) Inside-Out-Tracking
In this case, your Android Phone acts as the Object itself. For this, the phone needs to be calibrated first, to know, where to place the object in the virtual world. This happens by putting a QR-Code beneath the point, where the Quest/Quest 2s position gets resetted. Now the phone knows, where it is in the real world and sends the data over to the Quest/Quest 2 via PUN (Photon Unity Networking).

# 2) Outside-In-Tracking
In this case, your Android Phone acts as a basestation (pretty similar to Vive Basestations) and tracks your object in the space via a QR-Code, which is attached to the tracked object. For this, the phone needs to be calibrated first, to know, where to place the object in the virtual world. This happens by putting another QR-Code beneath the point, where the Quest/Quest 2s position gets resetted.


# COMING SOON... #
