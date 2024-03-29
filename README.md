# Medical Image Processing Project

### INSTRUCTIONS ON USING THE EVALUATION APPLICATIONS: 
-------------------------------------------------- 
The evaluation applications available in CBICA's IPP are: 
1. BraTS'18 Training Data: Segmentation Task 
2. BraTS'18 Training Data: Survival Task 
3. BraTS'18 Validation Data: Segmentation Task 
4. BraTS'18 Validation Data: Survival Task 

For the "Segmentation Task", note that the segmentations you upload in the evaluation applications must be named using only the subject ID and the extension nii.gz. The subject ID is given by the folder name containing the 4 modalities for each subject. In other words, you were given files called ID_t1.nii.gz, ID_t2.nii.gz, etc. Please upload segmentations called ID.nii.gz 

For the "Survival Task", the predicted survival data should be in a .csv file that has the subject ID in column 1 and the predicted survival values in days in column 2. The .csv should NOT contain ANY HEADER. 

Once your uploaded data are evaluated, you will receive an email pointing to a separate Results.zip file for each of the tasks, accessible via the IPP. Please note that there is a limit of concurrent evaluations that you can run, and a limit on the evaluations that you can have stored in the portal (n=10). Please make sure that you delete evaluations once you receive their results. 

Please make sure that whenever you use and/or refer to the BraTS datasets in your manuscripts, you should always cite the papers mentioned at: https://www.med.upenn.edu/sbia/brats2018/data.html 

Please contact brats2018@cbica.upenn.edu with any questions you may have. 

The BraTS bot (on behalf of the BraTS team).

### CONVENTIONS: 
1. LGG: lower grade glioma
2. HGG/GBM: glioblastoma
