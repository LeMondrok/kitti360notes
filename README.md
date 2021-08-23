# kitti360notes

## Convert into semanticKitti format

Suppose terminal in folder `dir`, dataset in folder `dataset_dir`, we want out updated dataset in `output_folder`

> `git clone https://github.com/JulesSanchez/recoverKITTI360label`
> `cd recoverkitti360label`  
> `conda create --name recoverkitti360 python=3.7`  
> `conda activate recoverkitti360`  
> `conda install numpy argparse matplotlib pillow scikit-image opencv open3d`  
> `python recoverLabels.py --kitti_dir dataset_dir --output_dir output_folder`

## Visualize

Follow the instructions from https://gitlab.com/sdbcs-nio3/itl_mipt/segm_tracking/utils/rviz_visualization

> `python vis_seg_cloud.py -pc point_cloud.bin -l corresponding_label.label` будет транслировать облако в соответствующий топик, который можно посмотреть через RViz


## Classes

> unlabeled  
> ego vehicle  
> rectification border  
> out of roi  
> static  
> dynamic  
> ground  
> road  
> sidewalk  
> parking  
> rail track  
> building  
> wall  
> fence  
> guard rail  
> bridge  
> tunnel  
> pole  
> polegroup  
> traffic light  
> traffic sign  
> vegetation  
> terrain  
> sky  
> person  
> rider  
> car  
> truck  
> bus  
> caravan  
> trailer  
> train  
> motorcycle  
> bicycle  
> garage  
> gate  
> stop  
> smallpole  
> lamp  
> trash bin  
> vending machine  
> box  
> unknown construction  
> unknown vehicle  
> unknown object  
> license plate  
