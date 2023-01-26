# Semantic-Gap-in-Medical-Image-Segmentation
Traditionally, encoder-decoder architecture has degraded segmentation accuracy due to semantic gaps. If it is minimized, the mean dice scores of tumor core cancer subtypes may increase. 
# BraTS_2021_Challenge
 A preliminary improvement is shown in the attached image (https://ln5.sync.com/dl/db427dd60/2cd3fwwu-vtyvtjzi-zxdf3bxv-gie6za43).
 Results of each table can be obtained through two docker images:
 1. BraTS 2018 (https://hub.docker.com/repository/docker/parvezamu/tmi_2018). Docker image can be downloaded using the command: docker pull parvezamu/tmi_2018
 The image gives outputs via the following command
 docker run --rm -v $HOME/input/:/input/ -v $HOME/output/:/output/ parvezamu/tmi_2018
 
 2. BraTS 2020 (https://hub.docker.com/repository/docker/parvezamu/tmi_2020). Docker image can be downloaded using the command: docker pull parvezamu/tmi_2020:v3
 The image gives outputs via the following command
 docker run --rm -v $HOME/input/:/input/ -v $HOME/output/:/output/ parvezamu/tmi_2020:v3
 

Acknowledgement:
Many thanks to the host of the BraTS datasets.
Datasets can be downloaded:
1. BraTS 2018 (https://www.med.upenn.edu/sbia/brats2018/data.html) 
2. BraTS 2020 (https://www.med.upenn.edu/cbica/brats2020/data.html)
