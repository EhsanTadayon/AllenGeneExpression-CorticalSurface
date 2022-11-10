# Allen Human Gene Expression Atlas Samples Mapped to Individual and Common (fsaverage) Space

1. Freesurfer V.6 pial/white matter cortical surface reconstructions using both T1-weight and T2-weighted MRIs for all 6 subjects: 

- H0351.1009
- H0351.1012
- H0351.1015
- H0351.1016
- H0351.2001
- H0351.2002

Reconstrucitons are available under ```data/images/reconall```. 

Note: T2-weighted MRIs were used to improve accuracy of pial surface reconstruction. 

2. Cortical samples were extracted and they were mapped onto white matter surface. 

3. Circular surface-based region-of-interests (ROIs) with 5 mm radius were created for each sample and is available for download under ```data/images/reconall/<subject>/samples/labels_in_subject_space```)

4. Circular ROIs were mapped to fsaverage space and are available for download under ```data/images/reconall/<subject>/samples/labels_in_fsaverage_space```

![ROIs](figures/right_rois_1cm.png)


