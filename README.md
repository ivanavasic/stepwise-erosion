# stepwise-erosion
Use to quantify fluorescence signal at various radial distances in a hPSC colony.

#Steps
1. Separate image stacks as individual channel images, and save to dir1 folder.
2. Create a dir2 folder. Within dir2, create subfolders titled "masks_image set_x", where x=1,2,3..total images to be analyzed.
    For example, if there are 4 image stacks, subfolders should be dir2/masks_image set_1, dir2/masks_image set_2, dir2/masks_image set_3, dir2/masks_image      set_4. 
3. Create dir3 folder where all thresholded individual channel images will be saved.
4. Create dir4 folder where results will be saved.

#Results Analysis
1. Fluorescence measurement results are exported into csv files for each image stack. "Result of Mask_outline11" is the outermost radial slice. Fluorescence measurements for each individual channel image are taken for every radial slice.
