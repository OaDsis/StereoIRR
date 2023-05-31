# Stereo Image Rain Removal via Dual-View Mutual Attention
Anonymous

### Abstract
This paper studies a relatively new deraining task termed stereo image deraining through exploiting the useful complementary information between the left and right views of stereo images. Stereo image restoration methods usually obtain better performance than monocular methods by learning the disparity between dual views either implicitly or explicitly. However, very few studies on stereo image rain removal have been done and existing methods still cannot make full use of the complementary information between two views, and we find it is because: 1) the rain streaks have more complex distributions in directions and densities, which severely damage the complementary information and pose greater challenges; 2) the disparity estimation is not accurate enough due to the imperfect fusion mechanism for the features between two views. To overcome such limitations, we propose a new Stereo Image Rain Removal method (StereoIRR) via sufficient interaction between two views, which incorporates: 1) a new Dual-view Mutual Attention (DMA) mechanism which generates mutual attention maps by taking left and right views as key information for each other to facilitate cross-view feature fusion; 2) a long-range and cross-view interaction, which is constructed with basic blocks and dual-view mutual attention, can alleviate the adverse effect of rain on complementary information to help the features of stereo images to get long-range and cross-view interaction and fusion. Notably, StereoIRR outperforms other related monocular and stereo image rain removal methods on several datasets.
![image](https://github.com/OaDsis/SGINet/blob/main/figures/model.png)

### Requirements
- Python 3.8.10
- torch 1.10.0+cu113
- torchvision 0.11.1+cu113

### Datasets
You can download **StereoCityscapes** datasets from [Baidu Drive](https://pan.baidu.com/s/13RTsCkseiXv5SuhpjZ_N7w) (Key: msy5).

### Results
You can download the results of StereoIRR from [Baidu Drive](https://pan.baidu.com/s/15IP6AOSKOIxsoQxOBoyImQ) (Key: pypx).
