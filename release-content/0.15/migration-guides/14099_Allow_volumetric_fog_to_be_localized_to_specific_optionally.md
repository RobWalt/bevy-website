- A `FogVolume` is now necessary in order to enable volumetric fog, in addition to `VolumetricFogSettings` on the camera. Existing uses of volumetric fog can be migrated by placing a large `FogVolume` surrounding the scene.