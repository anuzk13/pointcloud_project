# 3D segmentation

Project exploring 3D segmentation of pointclouds.


## Models for semantic segmentation:
- https://paperswithcode.com/sota/semantic-segmentation-on-stanford2d3d-1
- https://paperswithcode.com/task/3d-point-cloud-classification
	- https://github.com/isl-org/Open3D-ML
	- I will try to process the pointcloud file with this tool

```
conda activate open3d_segmentation
```

## Colmap

Used the script in gaussian splatting to create a pointcloud from a video...TODO integrate this in the project
https://colmap.github.io/format.html

![[Pasted image 20240305095524.png]]

To import the pointcloud 
select the images and database (in deformed) 
save the project and export as ply

![[Pasted image 20240305100322.png|650]]
## Open3D

- Installed using pip
- Issue running the demo resolved changing the default graphics card: https://github.com/isl-org/Open3D/issues/3317#issuecomment-1763367777

### Point clouds
https://www.open3d.org/docs/release/tutorial/geometry/pointcloud.html


