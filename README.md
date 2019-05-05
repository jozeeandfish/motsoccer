# motsoccer
Multiple object tracking benchmark

MOT-SOCCER benchmark

百度网盘下载链接：
链接：https://pan.baidu.com/s/14qEcmgzAca9DGVsYYkOfvw 
提取码：qtlo 


Annotation

For video sequences collected in the MOT-SOCCER benchmark, we devoted to accurately annotate tracking information of player as ground truth. Each video was labeled according to the following uniform standards.
1. Mark the object with a rectangular bounding box. The box should cover the complete player body as accurate as possible. 
2. Each sequence defines a region of interest (ROI). Only the objects whose posi-tion locates in the region of interest are marked.
3. When a serious occlusion occurs, the object should be still annotated.
4. Each annotated tracking object incorporates 2d coordinate, tracking id, and frame information.
5. A trajectory only corresponds to a unique tracking id, and each id of all trajec-tories is not repeated.
6. When the object moves out of the region of interest and appears again, anno-tates it with a new tracking id.
