# Computer Vision
不好意思，接下来都是中文了……
作为从事机器视觉已近一年的我来说，从最初的啥都不懂，到现在对一些问题能够有一定的想法，可以说还是有了很大的提高，希望在这个平台能够多分享一些对机器视觉问题的理解。

作为一个CS背景的人，在学习CV的路上遇到的一个很大的问题是————很多教材和博客的讲解充满了数学的概念但是最终没有落实到代码上，这对于CS专业的人来说实在是不过瘾，一个积分公式怎么能让我看清背后的本质？（大侠你能不能写成for循环……）

我想尽量站在CS的角度去描述每一个问题和算法，多帖代码少写公式，让CS的高手快速领悟CV的真谛。

## 目录

### BackGround/背景知识

#### [Differential Geometry/微分几何](background/differentialGeometry.md)
#### [Multi-variable Calculus/多变量微积分](background/mcalc/README.md)

### Optimized/优化

#### [Code/优化代码](opt/code.py)
#### [Steepest Descent/最速下降法](opt/steepest.md)
#### [Conjugate Descent/共轭梯度法](opt/cg.md)
#### [Convex Function/凸函数](opt/convex.md)
#### [Conjugate Function/共轭函数](opt/conjugatef.md)

### Line detection/直线检测

#### [Hough Transformation/霍夫变换](line/hough.md)
#### [LSD/线段检测](line/lsd.md)

### Edge-aware Filter

#### [Total Variation/全局变分](filter/tv.md)
#### [Rolling Guidance Filter](filter/rolling.md)
#### [Domain Transfom Filter](filter/dt_filter.md)
#### [Guided Filter](filter/guided.md)

### Filter/过滤

#### [Decolor/灰度化](filter/decolor.md)
#### [Fourier Transformation/傅里叶变换](filter/fourier.md)
#### [Wavelet Transformation/小波变换](filter/wavelet.md)

### Contrast Enhancement/对比增强

#### [AHE&CLAHE](enhance/clahe.md)

### Segmentation/分割

#### [Otsu&Niblack/二值化](seg/niblack.md)
#### [LevelSet/水平集](seg/levelset.md)

### Dimension Reduction/降维

#### [Product Quantization](dimensionR/pq.md)
#### [Local Linear Embedding](dimensionR/lle.md)

### Morphology/形态学

#### [Skeleton Extraction/骨架提取](mor/skeleton.md)

### Feature/特征抽取

#### [Shape Context/形状上下文](feature/shapeContext.md)
#### [Sift](feature/sift.md)
#### [Hog](feature/hog.md)
#### [LBP](feature/lbp.md)

### Tiny-Cnn/源码学习

#### [基本架构/基础知识](tiny_cnn/basic.md)
#### [网络层](tiny_cnn/layer.md)
#### [网络与优化](tiny_cnn/network.md)

