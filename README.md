# Voxelized meshes

## Sponza

[Sponza gltf source](https://github.com/KhronosGroup/glTF-Sample-Models/tree/master/2.0/Sponza)

Voxelized with [vengi-voxconvert](https://github.com/vengi-voxel/vengi) 0.0.21-dev

```sh
./vengi-voxconvert -set voxformat_scale 0.3 --input ~/glTF-Sample-Models/2.0/Sponza/glTF/Sponza.gltf --output ~/sponza.qb
```

![image](sponza-scale-0.3.png)

## Bistro

[Bistro fbx source](https://developer.nvidia.com/orca/amazon-lumberyard-bistro)

Voxelized with [vengi-voxconvert](https://github.com/vengi-voxel/vengi) 0.0.28-dev

```sh
./vengi-voxconvert -set voxformat_scale 0.3 --input ~/Bistro/Bistro.fbx --output ~/bistro.qb
```

![image](bistro-scale-0.3.png)


# Links

[vengi-voxel/vengi](https://github.com/vengi-voxel/vengi)
