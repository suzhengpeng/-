---
typora-root-url: img
typora-copy-images-to: img
---

# 论文阅读清单

##  图像拼接

- [ ] Parallax-robust surveillance video stitching [^1]

- [ ] SEAGULL : Seam-guided Local Alignment for Parallax-tolerant Image Stitching[^7]

- [ ] Object-centered image stitching [^9]

  > 将目标检测技术（object detection）与图像拼接技术结合 

## 语义分割

- [ ] Fully Convolutional Networks for Semantic Segmentation [^8]

  > 提出了FCN（全卷积网络）实现语义分割

- [ ] Large Kernel Matters--Improve Semantic Segmentation by Global Convolutional Network [^3]
- [ ] Learning a discriminative feature network for semantic segmentation [^4]
- [ ] Bisenet: Bilateral segmentation network for real-time semantic segmentation [^5]
- [ ] Ocnet: Object context network for scene parsing [^6]

## 目标检测

- [ ] Faster r-cnn: Towards real-time object detection with region proposal networks [^2]

  > 在 Fast R-CNN 上提出 Faster R-CNN
  > 
  > 提出RPN网络替换选择性搜索，提高了ROI的搜索效率，即：高效的产生ROI
  > 

## 其他

- [ ] Fast Online Object Tracking and Segmentation: A Unifying Approach [^10]

  > 将**目标分割**与**目标跟踪**结合
  >
  > 项目：<http://www.robots.ox.ac.uk/~qwang/SiamMask/>
  >
  > Arxiv: <https://arxiv.org/abs/1812.05050>
  >
  > Github: <https://github.com/foolwood/SiamMask>
  >

**参考文献：**

[^1]: He B, Yu S. Parallax-robust surveillance video stitching[J]. Sensors, 2016, 16(1): 7.

[^2]: Ren S, He K, Girshick R, et al. Faster r-cnn: Towards real-time object detection with region proposal networks[C]//Advances in neural information processing systems. 2015: 91-99.

[^3]: Peng C, Zhang X, Yu G, et al. Large Kernel Matters--Improve Semantic Segmentation by Global Convolutional Network[C]//Proceedings of the IEEE conference on computer vision and pattern recognition. 2017: 4353-4361.

[^4]: Yu C, Wang J, Peng C, et al. Learning a discriminative feature network for semantic segmentation[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2018: 1857-1866.

[^5]: Yu C, Wang J, Peng C, et al. Bisenet: Bilateral segmentation network for real-time semantic segmentation[C]//Proceedings of the European Conference on Computer Vision (ECCV). 2018: 325-341.

[^6]: Yuan Y, Wang J. Ocnet: Object context network for scene parsing[J]. arXiv preprint arXiv:1809.00916, 2018.

[^7]: Lin K, Jiang N, Cheong L F, et al. Seagull: Seam-guided local alignment for parallax-tolerant image stitching[C]//European Conference on Computer Vision. Springer, Cham, 2016: 370-385.

[^8]: Long J, Shelhamer E, Darrell T. Fully convolutional networks for semantic segmentation[C]//Proceedings of the IEEE conference on computer vision and pattern recognition. 2015: 3431-3440.

[^9]: Herrmann C, Wang C, Strong Bowen R, et al. Object-centered image stitching[C]//Proceedings of the European Conference on Computer Vision (ECCV). 2018: 821-835.

[^10]: Wang Q, Zhang L, Bertinetto L, et al. Fast Online Object Tracking and Segmentation: A Unifying Approach[J]. arXiv preprint arXiv:1812.05050, 2018.
