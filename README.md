
# *<center>RGBT-Tiny: A Large-Scale Benchmark for Visible-Thermal Tiny Object Detection</center>*

***RGBT-Tiny is a large-scale visible-thermal benchmark which consists of 115 high-quality paired image sequence, 93K frames and 1.2M manual annotations,and covers abundant targets and diverse senarios. Details of this dataset can be found in our paper. Over 81\% of targets are smaller than 16x16, and we provide paired bounding box annotations with tracking id to offer an extremely challenging benchmark with wide-range applications, such as RGBT fusion, detection and tracking.***<br><br>

## Sample Videos

<center class="half">
     <img src="pics/DJI_0028_5_00_gif.gif" width="240"/>&nbsp&nbsp&nbsp<img src="pics/DJI_0028_5_01_gif.gif" width="240"/>
 </center>

 <center class="half">
     <img src="pics/DJI_0067_2_00_gif.gif" width="240"/>&nbsp&nbsp&nbsp<img src="pics/DJI_0067_2_01_gif.gif" width="240"/>
 </center>

 <center class="half">
     <img src="pics/DJI_0075_3_00_gif.gif" width="240"/>&nbsp&nbsp&nbsp<img src="pics/DJI_0075_3_01_gif.gif" width="240"/>
 </center>

 <center class="half">
     <img src="pics/DJI_0101_2_00_gif.gif" width="240"/>&nbsp&nbsp&nbsp<img src="pics/DJI_0101_2_01_gif.gif" width="240"/>
 </center>

 <center class="half">
     <img src="pics/DJI_0229_2_00_gif.gif" width="240"/>&nbsp&nbsp&nbsp<img src="pics/DJI_0229_2_01_gif.gif" width="240"/>
 </center><br><br>

## Benchmark Properties

### Rich Diversity
<center><img src="pics/target_scene.jpg" width="512"/></center><br> 
Fig. 1 (a) Target distribution in visible and thermal modalities. (b) Scene distribution (inner circle) across different light visions (outer circle). 

### Large Density Variation
<center><img src="pics/density.jpg" width="300"/></center><br> 
Fig. 2 Density of each sequence. ($x$,$y$,$z$) are the numbers of sequences w.r.t. density levels (i.e., sparse, medium, dense).<br> 

### Small-Scale Targets
<center><img src="pics/scale.jpg" width="250"/></center><br>
Fig. 3 Size distribution of each target category.<br> 

### Temporal Occlusion
<center><img src="pics/occlusion.jpg" width="180"/></center><br>
Fig. 4 Temporal occlusion (i.e., no occlusion, slight occlusion, moderate occlusion, heavy occlusion).<br> <br> 

## Evaluation Metric
<center><img src="pics/evaluation.jpg" width="512"/></center>
Fig. 5 An illustration of SAFit measure. (a) Pixels deviation between the center points of GT bbox and predicted bbox. (b) IoU-Deviation curves w.r.t different sizes of bboxes. (c)-(d) SAFit-Deviation curves under different C values. <br><br>

### SAFit for evaluation
<center><img src="pics/dis_iou.jpg" width="512"/></center>
Fig. 6 Comparisons among different measures for performance evaluation in visible and thermal modalities.<br><br>

### SAFit loss for training
SAFit results achieved by ATSS equipped with different losses in visible and thermal modalities of RGBT-Tiny dataset. 
<center><img src="pics/table00.jpg" width="512"/></center>

SAFit and IoU results achieved by ATSS equipped with different losses in COCO dataset.
<center><img src="pics/table01.jpg" width="512"/></center><br><br>

## Baseline Results
Table 1 SAFit-based results of existing visible detection (V-D), visible SOD (V-SOD), thermal SOD (T-SOD), visible-thermal
detection methods (VT-D) methods on RGBT-Tiny dataset. 
<center><img src="pics/table1.JPG" width="512"/></center><br>

Table 2 IoU-based results of existing visible detection (V-D), visible SOD (V-SOD), thermal SOD (T-SOD), visible-thermal
detection methods (VT-D) methods on RGBT-Tiny dataset. 
<center><img src="pics/table2.JPG" width="512"/></center><br><br>

## Downloads
Downloads will be released upon acceptance.