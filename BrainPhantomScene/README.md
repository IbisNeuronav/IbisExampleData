# Brain Phantom Scene

This is a tutorial on how to register MR and US data using Ibis.
[**US Volume Reconstruction with GPU**](https://github.com/IbisNeuronav/Ibis/tree/master/IbisPlugins/GPU_VolumeReconstruction) and [**Rigid Resigtration with GPU**](https://github.com/IbisNeuronav/Ibis/tree/master/IbisPlugins/GPU_RigidRegistration) plugins are used for this purpose.

The directory consists of MR and US data of a brain phantom in MINC format. By loading the XML file into Ibis, a scene similar to the below one will be appeared:

![Brain Phantom Scene](https://github.com/Mamarzesk/IbisExampleData/blob/documentation/BrainPhantomScene/BrainPhantomScene.png "Brain Phantom Scene")

Below video shows how to perform the registration on this data.

![Brain Phantom](https://github.com/Mamarzesk/IbisExampleData/blob/documentation/BrainPhantomScene/IbisBrain.gif "Brain Phantom - MR to US registration")

The first step is to create a US volume based on the acquired US images, using **US Volume Reconstruction with GPU** plugin. As it can be seen, the edges of the two set of data are not matched. The second step is to use **Rigid Resigtration with GPU** plugin, in order to match the edges of the two datasets.