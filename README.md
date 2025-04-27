# cs532-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS532 Assignment 3  Solved](https://www.ankitcodinghub.com/product/cs532-homework-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120783&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS532 Assignment 3&nbsp; Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Submission Format. Electronic submission on Canvas is mandatory. Submit in a zip file, a single pdf file containing:

<ul>
<li>the source code,</li>
<li>brief of explana?ons of what was done,</li>
<li>images and screenshots of the model.</li>
<li>final ply model.</li>
</ul>
Problem 1. Download the <em>dancer </em>dataset from the course web page. The zip file contains images, silhoueTes and projec?on matrices for a single ?me instant of a dynamic scene. A simple ply file containing 8 points is also included. (Finally, it contains a Matlab script that may be helpful, but is not necessary for comple?ng this assignment.) The goal is to obtain a voxel-based reconstruc?on of the scene using the provided silhoueTes as inputs.

&nbsp;

<strong><em><u>Step 1. Define a voxel grid</u></em></strong> with <em>x&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>ranging from -2.5 m to 2.5 m, <em>y&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>from -3 to 3 m and <em>z&nbsp;&nbsp; </em>from 0 to 2.5 m. Set the size of each voxel so that the total number of voxels fits comfortably in the memory of your computer. You can start at lower resolu?on ini?ally to accelerate development. You may also chose to make the ini?al volume ?ghter, but this is strictly op?onal. In this part, the goal is to es?mate which voxels are occupied and which are free space.

<strong><em><u>Step 2. Determine the voxels forming the visual hull.</u></em></strong> Start with all voxels labeled as EMPTY. Project the 3D center of each voxel to all images and label as OCCUPIED only those voxels whose projec?on resides inside ALL the silhoueTes. Report the total number and what rela?ve por?on of all voxels are in the visual hull.

<strong><em><u>Step 3. Iden&lt;fy voxels that are in the reconstructed surface.</u></em></strong>&nbsp; Surface voxels are OCCUPIED voxels having at least one neighboring voxel labeled as EMPTY. Report the total number and what rela?ve por?on of all voxels are surface voxels.

<strong><em><u>Step 4. Determine the set of 3D points to include in the output. </u></em></strong>From the surface voxels aTained in Step 3, add to the output 3D model the 3D point of CENTER OF EACH FACE that neighbors with an EMPTY VOXEL.&nbsp;&nbsp; Report the number 3D point included in the model and compare with the number voxels in the surface. Are they the same? Discuss why this is the case.

<strong><em><u>Step 5. Determine a false-color RGB for each output 3D point. </u></em></strong>To color each point first determine the range bounding box (i.e. the min and max values in each spa?al dimension, i.e. X, Y, and Z) of “reconstructed” points. This will give you X_min, X_max, Y_min, Y_max, Z_min, Z_max. For each single 3D point assign for the RED color channel a value propor?onal to that point X coordinate by RED=255*(X-X_min)/(X_max-X_min). Color the GREEN and BLUE channel similarly using the Y and Z dimensions

<strong><em><u>Step 6. Write a PLY file.</u></em></strong> The output should be in ASCII ply format. Use the included ply file as a sample for how to create such as file. The number aker element vertex is the total number of ver?ces and has to be correct for the model to be displayed correctly. Each vertex is represented by three floa?ng point numbers for the coordinates and three unsigned characters for the RGB colors. Models can be visualized using Meshlab, which is available at hTp://meshlab.sourceforge.net/ and works on Windows, MacOSX and Linux.

<strong><em><u>Step 7.&nbsp; Determine a true-color RGB for each output 3D point. </u></em></strong>&nbsp;Color the model by assigning the per-channel median RGB values of the pixels to which a surface voxel projects into. When compu?ng the color for each voxel take visibility into account and only compute the median RGB values from the set of cameras/images that have a non-occluded view of the voxel<strong><em><u>. A poten&lt;al</u></em></strong> <strong><em><u>approach</u></em></strong> is as follows: To test visibility determine a vector for each surface vertex that points outward from the occupied volume to the cameras. If the voxels intersected along these vectors are ALL EMPTY then the camera can “see” the surface voxels. You are welcome/encouraged to try your own method.

<strong><em><u>Step 8. Write a PLY file.</u></em></strong>

Acknowledgement. The input images, silhoueTes and calibra?on parameters have been generated and made available by the

&nbsp;
