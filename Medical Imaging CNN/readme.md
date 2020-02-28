
# Automatic segmentation tool for medical imaging

## Introduction
Medical imaging plays a critical role in patient care, and is used in clinical activities such as diagnosis, surgical navigation and research. For neurosurgical procedures, a variety of imaging modalities are used for diagnosis, surgical planning and surgical navigation, including CT and MRI. The visualization of these images is typically performed on 2D monitors, which provide limited spatial information of 3D medical images such as CT, MRI and 3D endoscopy.


In collaboration with a medical device company based in Boston, Z Imaging is building an AR system to enhance neurosurgical navigation. Broadly, the system involves overlaying a volumetrically-rendered CT or MRI scan of the patient onto a depth capture of the same patient’s head and visualizing the overlaid scan on the patient’s head through an AR headset or tablet.

## Project description
An initial step in the process involves ‘segmenting’ the patients head from the CT or MRI scan, so that we can generate a 3D model of the head surface that we can then align to the depth capture of the patient’s head. The project will involve the development of a method to automatically segment a surface from an MRI or CT scan of a patient’s head. This should be performed on the 3-dimensional scan (as opposed to slice-by-slice), segmenting out the voxels that comprise the head. The ideal segmentation algorithm should be resistant to noise in the scans.




