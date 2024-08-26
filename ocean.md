# awesome-seafloor-dataset-method
## 我们的海底调研工作

**Seafloor海底数据集研究综述** 海底数据集在海洋研究中具有重要意义。通过分析这些数据，我们可以深入了解海底地形、海洋生物分布以及环境变化等方面的信息。主要的数据集来源包括GEBCO、NOAA和SRTM等，它们提供了高分辨率的全球海底地形数据。

---

根据海洋环境特征，我们可以将海洋数据分为地质数据、海底沉积物数据和海底元素。

> 地质数据：海底地形、海底地壳活动
> 
> 沉积物数据：海底沉积物分布、沉积物厚度
> 
> 元素数据：海底元素含量和分布

### 海底地质调研

#### 🌟GEBCO海洋数据

**数据集摘要**GEBCO数据的全称是General Bathymetric Chart of the Oceans (全球海洋通用水深数据) ，是由国际海道测量组织 (IHO) 和政府间海洋学委员会 (IOC) 联合发布的最全面的世界大洋海底地形数据，也是当今海洋模式中最常用的海洋水深数据之一。 GEBCO的数据主要来源于多波束声呐测深、卫星测高和其他海洋测量技术。这些数据经过处理和整合，生成了详细的海底地形图。

**基本信息**

- **分辨率**：GEBCO提供的地形数据分辨率高达30米。
- **覆盖范围**：全球海洋，包括深海和沿海区域。
- **数据格式**：NetCDF、GeoTIFF等多种格式，便于不同应用场景使用。

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/20240819193559.png)
![](https://cdn.jsdelivr.net/gh/lz-GitHub125/1/test/6f4f838765fcf5d37180752daed2315.png)

**数据下载**：https://mds.nmdis.org.cn/pages/dataViewDetail.html?type=3&did=&dataSetId=86-1

#### 🌟SRTM30 PLUS

**数据集摘要**：SRTM30 PLUS 数据集是一个全球性的地形数据集，结合了SRTM的陆地地形数据和多来源的海底测深数据，提供了30弧秒（约1公里）分辨率的全球地形信息。该数据集覆盖全球陆地和海底地形，广泛应用于地形分析、海洋研究、气候建模等领域。数据以NetCDF、GeoTIFF等格式提供，适用于地理信息系统和其他分析工具。SRTM30 PLUS 数据集持续更新，提供一致性和全面性的全球地形数据支持。

**基本信息**：

* **分辨率**：30弧秒（约一公里）
* **覆盖氛围**：全球陆地和海底地形
* **数据格式**：NetCDF

**不同海域海底地形可视化图**

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/20240826170130.png)
##### 🌟ETOPO1全球地形模型

**数据集摘要**：ETOPO全球地势模型整合了来自区域和全球数据集的地形、测深和海岸线数据，以实现地球表面地球物理特征的全面、高分辨率渲染。该模型旨在支持海啸预报、建模和预警，以及海洋环流建模和地球可视化。当前版本ETOPO 2022有冰面和基岩版本，描绘了覆盖格陵兰岛和南极洲的冰盖顶层，或下面的基岩。

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/20240826170313.png)

**数据集下载**：https://www.ncei.noaa.gov/products/etopo-global-relief-model

#### 🌟3弧秒（90 m）全球DEM数据集GDEM_2022

**数据集摘要**：GDEM_2022是由清华大学发布的全球3弧秒（约90米）分辨率的海陆数字高程模型数据集。该数据集利用深度学习和迁移学习技术，基于NASA和GEBCO数据，提供了比传统方法更精确的地形信息，支持全球气候变化、海洋研究等领域。

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/71aee5ebd3b3694aa9bf47a3e57fbde.png)

上图为3弧秒（90 m）全球DEM数据集GDEM_2022

**数据集下载**：https://cloud.tsinghua.edu.cn/d/695ed43696564904980f
#### 🌟 age.2020.1.GTS2012.6m.nc
**数据集摘要**: age.2020.1.GTS2012.6m.nc主要整合了全球海底地壳的年龄。该数据集包含的海洋地壳的年龄可以反映地壳形成和演化的过程，以及与之相关的地质活动。
![](https://cdn.jsdelivr.net/gh/lz-GitHub125/1/test/20240825124258.png)
#### 🌟 dir.2020.1.GeeK2007.6m.nc
**数据集摘要**：dir.2020.1.GeeK2007.6m.nc整合了海底扩张方向。该数据集包含的海底扩张方向是指海底地壳在洋中脊或板块边界处形成和移动的方向。
![](https://cdn.jsdelivr.net/gh/lz-GitHub125/1/test/20240825124454.png)
#### 🌟 obliq.2020.1.GeeK2007.6m.nc
**数据集摘要**：obliq.2020.1.GeeK2007.6m.nc整合了海底扩散倾角。海底扩散倾角是指海底扩张的方向与洋中脊垂直方向的夹角。
![](https://cdn.jsdelivr.net/gh/lz-GitHub125/1/test/20240825124627.png)
#### 🌟 asym.2020.1.GeeK2007.6m.nc
**数据集摘要**：asym.2020.1.GeeK2007.6m.nc整合了海底扩张不对称性，该数据集包含的海底扩张不对称性是指在海底扩张过程中，两侧的扩张速率或形态不一致的现象。
![](https://cdn.jsdelivr.net/gh/lz-GitHub125/1/test/20240825124805.png)
#### 🌟 age_misfit.2020.1.GeeK2007.6m.nc
**数据集摘要**：age_misfit.2020.1.GeeK2007.6m.nc整合了海底地壳年龄误差，该数据集包含的海底地壳年龄误差是指全球范围内年龄网格与年龄约束之间的误差。
![](https://cdn.jsdelivr.net/gh/lz-GitHub125/1/test/20240825125055.png)
#### 🌟 full_rate_bands.2020.1.GTS2012.6m.nc
**数据集摘要**：full_rate_bands.2020.1.GTS2012.6m.nc整合了海底地壳扩散率，该数据集包含的海底扩张速率是指海底地壳在洋中脊或板块边界处形成和移动的速度
![](https://cdn.jsdelivr.net/gh/lz-GitHub125/1/test/20240825125422.png)
#### 🌟 conf.2020.1.GeeK2007.6m.nc
**数据集摘要**：conf.2020.1.GeeK2007.6m.nc整合了海底地壳估计年龄可信度，其表示对地质年龄估计的可信度。
![](https://cdn.jsdelivr.net/gh/lz-GitHub125/1/test/20240825125741.png)

**论文链接**：https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2020GC009214

**数据集下载**：https://www.earthbyte.org/webdav/ftp/earthbyte/agegrid/2020/Grids/


### 海底沉积物调研：

#### 🌟GlobSed：世界海洋中最新的沉积物总厚度

**数据集摘要**：NCEI 的全球海洋沉积物厚度网格 Divins （2003） 由 Whittaker 更新 et al. （2013） 再次更新了东北大西洋、北极、南大洋、 和地中海地区。
![](https://cdn.jsdelivr.net/gh/lz-GitHub125/1/test/20240826144339.png)
**下载链接**:https://data.noaa.gov/metaview/page?xml=NOAA/NESDIS/NGDC/MGG/Geophysics/iso/xml/G01065_v3.xml&view=getDataView&header=none

#### 🌟Total Sediment Thickness of the World's Oceans and Marginal Seas, Version 2
**数据集摘要**：Total Sediment Thickness of the World's Oceans and Marginal Seas, Version 2提供了世界海洋和边缘海的沉积物厚度数据的全球网格。该数据集中的主要变量是沉积在海底和边缘海的沉积物的厚度。
![](https://cdn.jsdelivr.net/gh/lz-GitHub125/1/test/20240826144239.png)
**下载链接**：https://www.ngdc.noaa.gov/mgg/sedthick/sedthick.html


#### 🌟 Deep-sea sediments of the global ocean mapped with Random Forest machine learning algorithm
**数据集摘要**:该数据集提供了有关全球海洋深海沉积物分布和特征的信息。深海沉积物包括各种类型的材料。

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/b5e5b737ee8a83b3bf41047a639dd92.png)

**分别为钙质软泥、黏土、硅藻软泥、固体沉积物、放射虫软泥的可能性分布**

**下载链接**：https://doi.pangaea.de/10.1594/PANGAEA.911692

#### 🌟Total sediment thickness of the World’s Oceans & Marginal Seas, version 2 

**数据集摘要**：Total Sediment Thickness of the World’s Oceans & Marginal Seas, version 2 是一个全球性的海洋沉积物厚度数据库。这个数据集由Gaina等人在2019年通过Geochemistry, Geophysics, Geosystems期刊发表，名为GlobSed。它提供了一个5弧分钟分辨率的全球海洋和边缘海的总沉积物厚度网格28。与之前的全球网格相比，GlobSed覆盖了更大的区域，并且在北大西洋、北极、南大洋和地中海区域进行了更新，导致估算的总海洋沉积物体积增加了29.7%28。

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/1749768499028682ad438d146b81d26.png)

**图片表示了沉积物的厚度，范围由0-20000米**

**下载链接**：https://www.earthbyte.org/total-sediment-thickness-of-the-worlds-oceans-marginal-seas-version-2/

#### 🌟NGDC Seafloor Sediment Grain Size Database

**下载链接**：https://www.ngdc.noaa.gov/mgg/geology/data/g00127/

#### 🌟Deck41表层海底沉积物描述数据库

**下载链接**：https://www.ngdc.noaa.gov/mgg/geology/data/g02094/
### 海底元素调研：

#### 🌟多金属结核主量元素数据(Major elements of polymetallic nodule)

**数据集摘要** ：原始来源为国际海底管理局（ISA），对原始数据进行了表头规范化、信息补充、范围检验、统计分析、错误值剔除和排重等处理，形成多金属结核主量元素标准数据集。数据量共计1018站,2551个样品，空间范围覆盖全球大部分海域（-180°～180°E，-65.62°～66.68°N），数据要素项包括Mn、Fe、Co、Ni、Cu、Zn、Pb、Al、Si等元素百分含量。

**基本信息**：

* 空间范围：全球大部分海域（-180°～180°E，-65.62°～66.68°N）
* 数据格式：xls
![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/20240826184820.png)
**下载链接** ：https://mds.nmdis.org.cn/pages/dataViewDetail.html?type=1&did=&dataSetId=30
#### 🌟富钴结壳主量元素数据（Major elements of cobalt-rich crust）

**数据集摘要** ：原始来源为国际海底管理局（ISA），对原始数据进行了表头规范化、信息补充、范围检验、统计分析、错误值剔除和排重等处理，形成富钴结壳主量元素标准数据集。数据量共计1203站,3286个样品，空间范围覆盖全球大部分海域（-180°～180°E，-64.18°～56.17°N），数据要素项包括Cu、Ni、Fe、Co、Si、Pb、Al、Mn、Zn等元素百分含量。

**下载链接**：https://mds.nmdis.org.cn/pages/dataViewDetail.html?dataSetId=21


## 海底数据集下载

### 海底地质数据集下载

|                          数据集名称                          |                          数据集简介                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [GEBCO海洋数据](https://mds.nmdis.org.cn/pages/dataViewDetail.html?type=3&did=&dataSetId=86-1) | 数据来源于全球海陆数据库（GEBCO），全球海陆栅格地形数据，数据分辨率为30″，约为900m，数据公布时间为2014年。 |
| [ETOPO全球地势模型](https://www.ncei.noaa.gov/products/etopo-global-relief-model) | ETOPO全球地势模型整合了来自区域和全球数据集的地形、测深和海岸线数据，以实现地球表面地球物理特征的全面、高分辨率渲染。 |
| [3弧秒（90 m）全球DEM数据集GDEM_2022](https://cloud.tsinghua.edu.cn/d/695ed43696564904980f) | GDEM_2022是由清华大学发布的全球3弧秒（约90米）分辨率的海陆数字高程模型数据集。该数据集利用深度学习和迁移学习技术，基于NASA和GEBCO数据，提供了比传统方法更精确的地形信息，支持全球气候变化、海洋研究等领域。 |
| [age.2020.1.GTS2012.6m.nc](https://www.earthbyte.org/webdav/ftp/earthbyte/agegrid/2020/Grids/) | 新的海洋地壳年龄网格以及扩散速率、不对称性、方向性和倾斜度的互补网格 |全球不同地区的海底地壳年龄|
| [age_misfit.2020.1.GeeK2007.6m.nc](https://www.earthbyte.org/webdav/ftp/earthbyte/agegrid/2020/Grids/)|全球范围内年龄网格与年龄约束之间的误差|
| [full_rate_bands.2020.1.GTS2012.6m.nc](https://www.earthbyte.org/webdav/ftp/earthbyte/agegrid/2020/Grids/)|海底扩张速率指海底地壳在洋中脊或板块边界处形成和移动的速度|
| [dir.2020.1.GeeK2007.6m.nc](https://www.earthbyte.org/webdav/ftp/earthbyte/agegrid/2020/Grids/)|海底扩张方向是指海底地壳在洋中脊或板块边界处形成和移动的方向|
| [conf.2020.1.GeeK2007.6m.nc](https://www.earthbyte.org/webdav/ftp/earthbyte/agegrid/2020/Grids/)|地质年龄估计的可信度|
| [obliq.2020.1.GeeK2007.6m.nc](https://www.earthbyte.org/webdav/ftp/earthbyte/agegrid/2020/Grids/)|海底扩张的方向与洋中脊垂直方向的夹角|
| [asym.2020.1.GeeK2007.6m.nc](https://www.earthbyte.org/webdav/ftp/earthbyte/agegrid/2020/Grids/)|海底扩张不对称性是指在海底扩张过程中，两侧的扩张速率或形态不一致的现象|
| [SRTM30 PLUS](https://topex.ucsd.edu/pub/srtm30_plus/srtm30/grd/)|SRTM30 PLUS 数据集是一个全球性的地形数据集，结合了SRTM的陆地地形数据和多来源的海底测深数据，提供了30弧秒分辨率的全球地形信息|

### 海底沉积物数据集下载

|                          数据集名称                          |                          数据集简介                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [Deep-sea sediments of the global ocean mapped with Random Forest machine learning algorithm](https://doi.pangaea.de/10.1594/PANGAEA.911692) |         对全球海洋深海沉积物的海底岩性进行了空间预测         |
| [Total sediment thickness of the World’s Oceans & Marginal Seas, version 2](https://www.earthbyte.org/total-sediment-thickness-of-the-worlds-oceans-marginal-seas-version-2/) |                世界海洋和边缘海的总沉积物厚度                |
| [NGDC Seafloor Sediment Grain Size Database](https://www.ngdc.noaa.gov/mgg/geology/data/g00127/) | NGDC海底沉积物粒度数据库包含全球 17,000 多个海底样本的粒度数据 |
| [Deck41 表层海底沉积物描述数据库](https://www.ngdc.noaa.gov/mgg/geology/data/g02094/) |  Deck41 是全球 36,401 个海底样本的表层沉积物成分的数字摘要   |
|[ Deep-sea sediments of the global ocean mapped with Random Forest machine learning algorithm](https://data.noaa.gov/metaview/page?xml=NOAA/NESDIS/NGDC/MGG/Geophysics/iso/xml/G01065_v3.xml&view=getDataView&header=none)|NCEI 的全球海洋沉积物厚度网格 Divins 由 Whittaker 更新 et al. 再次更新了东北大西洋、北极、南大洋、 和地中海地区。|
| [Total Sediment Thickness of the World's Oceans and Marginal Seas, Version 2](https://www.ngdc.noaa.gov/mgg/sedthick/sedthick.html)|世界海洋和边缘海域的数字总沉积物厚度数据库由 NOAA 国家地球物理数据中心 （NGDC）|

### 海底元素数据集下载

|                          数据集名称                          |                          数据集简介                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [多金属结核主量元素数据](https://mds.nmdis.org.cn/pages/dataViewDetail.html?type=1&did=&dataSetId=30) | 数据量共计1018站,2551个样品，空间范围覆盖全球大部分海域（-180°～180°E，-65.62°～66.68°N），数据要素项包括Mn、Fe、Co、Ni、Cu、Zn、Pb、Al、Si等元素百分含量。 |
| [富钴结壳主量元素数据](https://mds.nmdis.org.cn/pages/dataViewDetail.html?dataSetId=21) | 数据量共计1203站,3286个样品，空间范围覆盖全球大部分海域（-180°～180°E，-64.18°～56.17°N），数据要素项包括Cu、Ni、Fe、Co、Si、Pb、Al、Mn、Zn等元素百分含量。 |
