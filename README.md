# Shipping Container Style Screw Storage
[English version](./README.md) | [中文版](./README_ch.md)
Lid | Label lid
:----:|:----:
![Main visual](./_fig/main_visual.jpg) | ![Top label visual](./_fig/top_label_visual.jpg)



## Introduction
This is a modular screws/parts container design with various dimensions available.

This design uses a single base unit called base_length (available in 30mm, 40mm, and 50mm).
All container dimensions are simple multiples of this base unit:

+ Height = h × base_length
+ Length = L × base_length
+ Width = W × base_length

For example, a 30mm h1×L3×W2 container has dimensions of 30mm × 90mm × 60mm.

Each container comes with a matching lid and interchangeable labels. The repository includes hundreds of ready-made labels to choose from.

## Features: Two Formats
Stack | Flat in a tray
:-------:|:--------:
![Stack containers](./_fig/stack_containers.jpg) | ![Tray visual](./_fig/tray_visual.jpg)

 The design is stackable for containers with the same "base_length".
 
 If you don't want the lid and the stackability, an alternative option is to print a top label without a lid and put containers on a tray. Trays also come with different dimensions.

## Who Might Be Interested
+ You need storage for screws or small parts.
+ You only have a few variations of parts but don’t want to print a large case.
+ You want individual containers that can be enclosed and carried around without a huge case.
+ You don’t want to create labels manually yourself for common part types. Just choose from the files I generated.
+ You want very sturdy containers.
+ You like shipping container style.

## Variations
For each "base_length" (30mm, 40mm, 50mm), the container has different multiples in each direction. The height grid can be 1-2, length grid can be 1-3, and width grid can be 1-3.

![Container dimension](./_fig/container_dimension.png)

Containers have file names in the format {base_length}_h{height_grid}_L{length_grid}_W{width_grid}.

The figure above shows how the file names are related to the models.

For example [container_30mm_h1xL3xW2](./Containers/container_30mm/container_30mm_h1xL3xW2.STL) means the container's height, length, and width are (30, 90, 60) mm.

## Steps
![Steps](./_fig/steps.PNG)
1. Choose the format of containers.
2. Find the container .stl files from the folder, import into slicer, and split the model into objects (container and lid).
3. Choose the desired label from the folder and import to the slicer. Split the model into separate parts (container body and lid/label) using your slicer’s split function.
4. Print and assemble!
5. When putting on the lid, there should be a small "click" sound.

> To put on the labels, simply press and click into the hole.
> 
> If you don’t plan to change the label or feel it is not secure, applying some super glue may help.

## Simple Guide
The models are composed of multiple bodies and may be tricky for new 3D printing hobbyists to work with.

To see further guides, please see [Guide](./guide.md) for setting slicers (Bambu Studio in this case).

## 3D Models
Containers | Labels | Trays
:---: | :---: | :---:
30mm <br/> 40mm <br/> 50mm <br/> 30mm_toplabel <br/> 40mm_toplabel <br/> 50mm_toplabel | Side_label <br/> Top_label | 30mm <br/> 40mm <br/> 50mm
![container model](./_fig/container_model.PNG)| ![container model](./_fig/label_model.PNG) | ![container model](./_fig/tray_model.PNG)

### Screw Types to Choose From

Nut | Hex | Socket hex| Heat insert
:----:|:---:|:-----------:|:------:
Phillips | Slot | Square |

This figure explains the meaning of each symbol. Hope this is straightforward.
![Symbol legend](./_fig/legends.PNG)


## Note
+ Print with brims may be helpful to keep the bottom surface flat.
+ Due to the large number of potential screw variations, there must be some labels that people want but not provided. Please leave a comment to request them.

## License
This repository adopts [Creative Commons Attribution-NonCommercial (CC By-NC 4.0)](./LICENSE). Please do not use it for commercial purposes.

Also, this design was drawn with SolidWorks Education license so commercial use should not be considered.

Feel free to build new designs based on this.

## Contact
Email: wy.will.chou@gmail.com
