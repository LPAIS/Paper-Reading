## 2018 第五周 20180326-0401

<ol>
  <li><b>
    A Fast Parallel Algorithm for Thinning Digital Patterns.
    </b></li>
  <p>
    Zhang-Sue算法，实现二值化图像的细化。
    </p>
  <li><b>
    A New Thinning Algorithm for Binary Images。
    </b></li>
  <p>
    一种改进的细化算法，结合了ZS算法和子域算法，解决了ZS算法出现的有冗余像素、过腐蚀等问题。
    </p>
  </ol>

## 2018 第八周 20180423-0429

<ol>
  <li>
    <b>Marius Bulacu,Lambert Schomaker and L. Vuurpijl,Writer identification using edge-based directional features.
in Proceedings of the International Conference on Document Analysis & Recognition(2003)
    </b></li>
  <p>
    这篇文章讲了两种图像特征提取的方法，一种是Edge-direction特征提取，首先要使用Sobel算子提取边缘，然后对边缘像素点根据与x正轴的角度进行特征提取；另一种是Edge-hinge特征提取，与Edge-direction特征提取相似，Edge-hinge特征提取也需要首先提取边缘，然后利用类似于铰链的边在边缘像素的360度范围内进行特征提取。相比于第一种方法，第二种方法的效果更好一些。
    </p>
  <li><b>
    Li X,Ding X,Writer identification of chinese handwriting using grid microstructure feature,in Proceedings of the International Conference on Biometrics(2009)pp.1230-1239
    </b></li>
  <p>
 本篇文章讲了利用基于网格微结构的特征提取的方法，首先要使用Sobel算子提取边缘，然后在边缘像素的（2L-1）*（2L-1）的的范围内找到同环内相邻黑色点出现的次数，尺度在2以内的相邻环的相邻黑点出现的次数，最后利用改进的加权欧氏距离和改进的加权卡方距离进行相似度排序。
    </p>
  </ol>
## 2018 第九周 20180430-0505

<ol>
  <li>
    <b>David G.Lowe,Distinctive Image Features from Scale-Invariant Keypoints,International journal of computer vision,vol.60,no.2,pp. 91–110,2004.
    </b></li>
  <p>这篇文章讲了一种改进的SFIT算法，SFIT是图像的局部特性，其对旋转、尺度缩放、亮度变化保持不变性，对视角变化、仿射变换和噪声也保持一定程度的稳定。
    </p>
  <li><b>
    Li X,Ding X,Writer identification of chinese handwriting using grid microstructure feature,in Proceedings of the International Conference on Biometrics(2009)pp.1230-1239
    </b></li>
  <p>
 本篇文章讲了利用基于网格微结构的特征提取的方法，首先要使用Sobel算子提取边缘，然后在边缘像素的（2L-1）*（2L-1）的的范围内找到同环内相邻黑色点出现的次数，尺度在2以内的相邻环的相邻黑点出现的次数，最后利用改进的加权欧氏距离和改进的加权卡方距离进行相似度排序。
    </p>
  </ol>
