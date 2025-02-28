﻿ This simulation code package is mainly used to reproduce the results of the following paper [1]:

[1] D. Shen and L. Dai, “Dimension reduced channel feedback for reconfigurable intelligent surface aided wireless communications,” IEEE Trans. Commun., 2021. 

*********************************************************************************************************************************
If you use this simulation code package in any way, please cite the original paper [1] above. 
 
The author in charge of this simulation code pacakge is: Decai Shen (email: sdc18@mails.tsinghua.edu.cn).

Reference: We highly respect reproducible research, so we try to provide the simulation codes for our published papers (more information can be found at: 
http://oa.ee.tsinghua.edu.cn/dailinglong/publications/publications.html). 

Please note that the MATLAB R2020a is used for this simulation code package,  and there may be some imcompatibility problems among different MATLAB versions. 

Copyright reserved by the Broadband Communications and Signal Processing Laboratory (led by Dr. Linglong Dai), Beijing National Research Center for Information Science and Technology (BNRist), Department of Electronic Engineering, Tsinghua University, Beijing 100084, China. 
*********************************************************************************************************************************
Abstract of the paper: 

Reconfigurable intelligent surface (RIS) has recently received extensive research interest due to its capability to intelligently change the wireless propagation environment. For RIS-aided wireless communications  in  frequency division duplex (FDD) mode,  channel feedback at the user equipment (UE) is essential for the base station (BS) to acquire the downlink channel state information (CSI). In this paper, a dimension reduced channel feedback scheme is proposed to reduce the channel feedback overhead by exploiting the single-structured sparsity of  BS-RIS-UE cascaded channel. Since different UEs share the same sparse BS-RIS channel but have their respective   RIS-UE channels, there are only limited non-zero column vectors in the BS-RIS-UE cascaded channel matrix, and different UEs share the same indexes of the non-zero columns. Thus, the downlink CSI can be decomposed into  \emph{user-independent} channel information (i.e., the indexes of  non-zero columns) and \emph{user-specific} channel information (i.e., the non-zero column vectors), where the former for all UEs can be fed back by only one UE, while the latter can be fed back with a fairly low overhead by different UEs, respectively. Simulation results show that,  compared with the conventional method, the proposed  scheme can reduce  channel feedback overhead by more than 80 % for RIS-aided wireless communications.
*********************************************************************************************************************************
How to use this simulation code package?

All figures can be generated by running the corresponding .m file.

For example, you can generate the Figure 4 (for the achievable sum-rate comparison between the proposed dimension reduced channel feedback scheme and the conventional feedback scheme) by running FIG4_Parfor.m in the FIG4 folder.

p.s. All the codes of this paper are supported by "parfor" structure of Matlab to  improve the computing speed. If your PC does not support it, just revise the "parfor" as "for" in the codes of the main function.
*********************************************************************************************************************************
Enjoy the reproducible research!