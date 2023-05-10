#  U-Net Model
U-Net model is used as segmentation technique, our model is little bit different about normal architecture
>This serves as the assignment for the SatelliteImagery course taught to senior students in CUFE for 2023.

## Technologies 📚
<br>
<div align='center'>
<img src="https://github.com/Iten-No-404/COVID-Vaccine-Stance-Detection/blob/main/pytorch.png"  width="25%">
</div>
<br>

## Model 
 We built Unet Model which is divided into two main steps: <br>
 - Encoding
    - 3x3 Double Convolution
    - 2x2 Down Sampling (Max Pooling)
 - Decoding
    - 3x3 Double Convolution
    - 2x2 Up Sampling (Up Convolution)
    - 1x1 Convolution (Last layer only with the number of classes as the depth)

 We needed to do nearest neighbor interpolation because our images had small sizes (192*192). By doing so, we were able to improve the results and losses.<br>

## Results
<br>


<img src="https://github.com/radwaahmed2132000/U-net-Model/blob/main/results.jpeg" >


<br>

### Resource & References 
U-Net's Official Research Paper:
https://doi.org/10.48550/arXiv.1505.04597


## Collaborators

<div align='center'>

<!-- readme: collaborators -start -->

|  <img src="https://avatars.githubusercontent.com/u/56734728?v=4" width="100;" alt="radwaahmed2132000"/> | <img src="https://avatars.githubusercontent.com/u/56697800?v=4" width="100;" alt="Iten-No-404"/> |  
| ------------------------------------------------------------------------------------------------------- |----------------------------------------------------------------
 <a href="https://github.com/radwaahmed2132000">Radwa Ahmed</a>  |   <a href="https://github.com/Iten-No-404">Iten Elhak</a>

 </div>
<!-- readme: collaborators -end -->

