# awesome-seafloor-dataset-method
## 我们的海洋调研工作

**Sea海洋数据集研究综述** 海洋数据集在海洋研究中具有重要意义。通过分析这些数据，我们可以深入了解海洋生物分布以及环境变化等方面的信息。主要的数据集来源包括GEBCO、NOAA和SRTM等，它们提供了高分辨率的全球海洋水文和气象数据。

---

根据海洋环境特征，我们可以将海洋数据分为水文数据和生物数据。

> 水文数据：盐度、温度、浊度
>
> 生物数据：浮游动植物、鱼类及其他海洋生物
>
> 生化参数:硅酸盐、叶绿素、溶解氧等

### 海洋水文数据的调研
#### **全球0.5度海洋盐度格点数据产品（Global ocean salinity grid data product with 0.5-degree spatial resolution）**

**数据集摘要** ：全球0.5度海洋盐度数据集的原始数据来自全球海洋数据库（WOD）中的所有现场观测数据，包括CTD, Argo, Bottle, Glider, mooring等观测仪器。该数据集主要基于大气所提出的集合最优插值方法对数据进行空间插值，该方法利用CMIP5多模式的历史模拟和高分辨率样本提供动力集合样本。

**基本信息** ：

时间范围：1960/01-2020/12	 水平分辨率：$0.5°\times0.5°$

空间区域：全球			      垂直分辨率：0-2000米，共41层

经度范围：180°W~180°E	      时间分辨率：月平均

纬度范围：90°S~90°N		   储存格式：nc

要素信息：盐度			      关键词：盐度；全球；全球变化

![2014年12月全球0.5度海表盐度](https://applet.casodc.com//files/metadata/images/salinity_in_IAP_05_sss_year_2014_month_12-1636567603715.png)

**下载链接** ：http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1456516931682066433&otherId=1456516931803701249

### **IAP全球海洋温度1°格点数据集(IAP Global Ocean Temperature 1° Gridded Dataset)**
**基本信息** :

时间范围:1940/01-2023/12          水平分辨率:  1° 

空间区域:  全球               垂直分辨率:  0-6000m; 119层

经度范围:  180°W~180°E         时间分辨率:  逐月

纬度范围:  90°S~90°N          存储格式:  NetCDF

要素信息:  温度               关键词:  温度;全球 

![](https://cdn.jsdelivr.net/gh/lz-GitHub125/1/test/IAP%20temp-1705313270219.png)
**下载链接** ：http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1746836580808540162&otherId=1746836581001478146

### **全球海洋盐度数据集(Global Ocean Salinity Dataset)**
**数据集摘要** ：由中科院海洋大科学研究中心共建单位大气所成里京研究员和朱江研究员牵头研制的全球海洋温度数据集，主要基于XBT、CTD、Argo、MBT、Glider等所有可搜集到的现场观测数据。
时间范围:  1940/01-2023/09          水平分辨率:  1°×1°

空间区域:  全球                  垂直分辨率:  海洋上层0-2000米，共41层

经度范围:  180°W~180°E             时间分辨率:  monthly Average

纬度范围:  90°S~90°N              存储格式:  nc

要素信息:  温度; 全球; 全球变化       关键词:  Tempreture; GLOBAL; GLOB

![](https://cdn.jsdelivr.net/gh/lz-GitHub125/1/test/global-salinity-1621388480232.png)

**下载链接** : http://msdc.qdio.ac.cn/data/metadata-special-detail?id=9&otherId=3


#### **全球0.5度海洋温度格点数据产品(Global ocean temperature grid data product with 0.5-degree spatial resolution)**

**数据集摘要**：全球0.5度海洋温度数据集的原始数据来自全球海洋数据库（WOD）中的所有现场观测数据，包括XBT, CTD, Argo, Bottle, MBT, Glider, mooring等观测仪器。该数据应用了大气所提出的XBT数据偏差订正方案（CH14方案）对历史XBT数据进行偏差订正。同时，使用了大气所提出的插值方法（Mapping：改进的集合最优插值）对数据进行空间插值，该方法利用CMIP5多模式的历史模拟和高分辨率样本提供动力集合样本。

**基本信息**：

时间范围：1960/01-2020/12			水平分辨率：0.5°x0.5°

空间区域：全球					    垂直分辨率：0-2000米，共41层

经度范围：180°W~180°E			     时间分辨率：月平均

纬度范围：90°S~90°N				  存储格式：nc

要素信息：温度					     关键词：温度；全球；全球变化

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/Temp_10m_2020_01-1636567791928.png)

**下载链接**：http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1456577680076988418&otherId=1456577680144097281

#### **全球0.1度高分辨率海洋环流模式HYCOM数据产品（HYCOM Global 0.1-degree high-resolution ocean circulation model data products）**

**数据集摘要**：该数据集是基于HYCOM2.3.01高分辨率准全球海洋模式，对全球温度、盐度、环流的模拟结果。该模式的空间范围为75°S-75°N，纬向与经向分辨率均为0.1°，垂向50层，时间分辨率为30日平均。采用ETOPO1数据改进模式地形，利用ERA5逐时大气变量驱动CTRL实验。

**基本信息：** 

时间范围：2013/01-2022/09			水平分辨率：0.1°

空间范围：准全球					垂直分辨率：3m~500m

经度范围：180°E~180°E				时间分辨率：30日

纬度范围：75°S~75°N				储存格式：NC

要素信息：温度；盐度；海流			关键词：海流；模式；全球；高分辨率；温度

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/20240818103408.png)

**下载链接**：http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1777794551860174850&otherId=1777794551939866626

#### **Sea Surface Salinity, Miras SMOS, Near Real-Time, Global 0.25°, 2010-present, 3 Day Composite**

**数据集摘要**：该数据集提供了自2010年以来的全球海表盐度（Sea Surface Salinity, SSS）的近实时观测数据，分辨率为0.25°。数据来源于欧洲航天局（ESA）的微波辐射成像卫星MIRAS（Microwave Imaging Radiometer with Aperture Synthesis），该卫星是土壤湿度和海洋盐度（SMOS, Soil Moisture and Ocean Salinity）任务的一部分。数据集通过每3天合成一次，提供了全球海表盐度的时空分布信息，适用于气候研究、海洋循环模式分析以及与海洋和大气过程相关的各类应用。这些数据可以帮助研究者深入了解全球水循环、海洋动态及其对气候变化的响应。

**可视化图片**：第一个时间点为例

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/image-20240816151044461.png)

**下载链接**：https://coastwatch.pfeg.noaa.gov/erddap/zh-CN/files/coastwatchSMOSv662SSS3day/2023/

### 海洋生物数据的调研

#### COPEPOD海洋生物数据集(COPEPOD marine biology dataset)

**数据集摘要**：数据来源于美国国家海洋渔业中心海岸带与海洋浮游生态、生产和观测数据库，数据集区域为全球。西边经度：-180.0，东边经度：180.0，南边纬度：-78.5，北边纬度：89.0。数据起始时间为：1913.08.30-2013.08.29。共213821个站次。

**下载链接**：https://mds.nmdis.org.cn/pages/dataViewDetail.html?dataSetId=59

#### 10米高分辨率全球红树林分布数据集(HGMF_2020)

**数据集摘要**：可持续发展大数据国际研究中心（SDG中心）在高精度全球红树林制图研究方面取得进展，研制了首套高空间分辨率（10米）的全球红树林分布数据集（HGMF_2020）。利用遥感大数据和Google Earth Engine（GEE）云平台，集成影像最大值合成算法（MSIC）以及面向对象随机森林算法（OBRF），提出了一种高效、高精度、高鲁棒性的红树林制图方法体系，构建了首套高空间分辨率（10米）的全球红树林分布数据集，命名为HGMF_2020。

![](https://cdn.jsdelivr.net/gh/zzh5560/Image-hosting-service/img/image-20240816174057030.png)

**论文** ：https://doi.org/10.1016/j.scib.2023.05.004

**下载链接**：https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/PKAN93

#### GLOBEC NEP MOCNESS Plankton (MOC1) Data, 2000-2002

**数据集摘要**：该数据集来源于GLOBEC（Global Ocean Ecosystem Dynamics）项目的东北太平洋（NEP）子计划，具体收集时间为2000年至2002年。MOCNESS（Multiple Opening/Closing Net and Environmental Sensing System）是一种用于收集不同深度的浮游生物样本的系统。通过MOC1设备，研究人员能够获取分层的浮游生物数据，包括生物量、物种组成和丰度等关键信息。

该数据集的核心是通过多次海洋采样，了解浮游生物的垂直分布特征以及其对环境变化的响应。数据可以用于研究海洋生态系统的动态变化、食物网结构、以及与气候变化相关的生态学问题，帮助深入理解海洋生态系统对环境变化的适应机制。

![img](https://coastwatch.pfeg.noaa.gov/erddap/zh-CN/tabledap/erdGlobecMoc1.png?longitude,latitude,cast_no&time%3E=2000-05-24T00%3A00%3A00Z&time%3C2002-05-31T00%3A00%3A00Z&longitude%3E=-128.01&longitude%3C=-120.01&latitude%3E=40.94&latitude%3C=48.94&.draw=markers&.marker=5%7C5&.color=0x000000&.colorBar=%7C%7C%7C%7C%7C&.bgColor=0xffccccff)

**数据集下载**：https://coastwatch.pfeg.noaa.gov/erddap/zh-CN/files/erdGlobecMoc1/

#### Image dataset of common benthic foraminifera in surface sediments of the North Atlantic Ocean

**数据集摘要**：北大西洋表层沉积物中底栖有孔虫的图像数据集提供了106种不同类群的显微照片，这些数据对于研究海洋环境和古海洋学至关重要。这些有孔虫是了解海底环境条件的关键指标，图像集有助于物种识别和环境重建。

**数据集下载**：https://doi.org/10.1016/j.dib.2019.104554

## 海底数据集下载

### 海洋水文数据集下载

|                          数据集名称                          |                          数据集简介                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [全球0.5度海洋盐度格点数据产品](http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1456516931682066433&otherId=1456516931803701249) | 全球0.5度海洋盐度数据集的原始数据来自全球海洋数据库（WOD）中的所有现场观测数据，包括CTD, Argo, Bottle, Glider, mooring等观测仪器。 |
| [IAP全球海洋温度1°格点数据集](http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1746836580808540162&otherId=1746836581001478146) | 该数据集的原始数据为来自全球海洋数据库（WOD）中的所有现场观测数据 |
| [全球0.5度海洋温度格点数据产品](http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1456577680076988418&otherId=1456577680144097281) | 全球0.5度海洋温度数据集的原始数据来自全球海洋数据库（WOD）中的所有现场观测数据，包括XBT, CTD, Argo, Bottle, MBT, Glider, mooring等观测仪器。 |
| [全球0.1度高分辨率海洋环流模式HYCOM数据产品](http://msdc.qdio.ac.cn/data/metadata-special-detail?id=1777794551860174850&otherId=1777794551939866626) | 该数据集是基于HYCOM2.3.01高分辨率准全球海洋模式，对全球温度、盐度、环流的模拟结果。该模式的空间范围为75°S-75°N，纬向与经向分辨率均为0.1°，垂向50层，时间分辨率为30日平均。 |
| [Sea Surface Salinity, Miras SMOS, Near Real-Time, Global 0.25°, 2010-present, 3 Day Composite](https://coastwatch.pfeg.noaa.gov/erddap/zh-CN/files/coastwatchSMOSv662SSS3day/2023/) | 该数据集提供了自2010年以来的全球海表盐度（Sea Surface Salinity, SSS）的近实时观测数据，分辨率为0.25°。数据来源于欧洲航天局（ESA）的微波辐射成像卫星MIRAS（Microwave Imaging Radiometer with Aperture Synthesis），该卫星是土壤湿度和海洋盐度（SMOS, Soil Moisture and Ocean Salinity）任务的一部分。 |

### 海洋生物数据集下载

|                          数据集名称                          |                          数据集简介                          |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [COPEPOD海洋生物数据集](https://mds.nmdis.org.cn/pages/dataViewDetail.html?dataSetId=59) | 数据来源于美国国家海洋渔业中心海岸带与海洋浮游生态、生产和观测数据库，数据集区域为全球。西边经度：-180.0，东边经度：180.0，南边纬度：-78.5，北边纬度：89.0。数据起始时间为：1913.08.30-2013.08.29。共213821个站次。 |
| [10米高分辨率全球红树林分布数据集](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/PKAN93) | 可持续发展大数据国际研究中心（SDG中心）在高精度全球红树林制图研究方面取得进展，研制了首套高空间分辨率（10米）的全球红树林分布数据集（HGMF_2020）。 |
| [GLOBEC NEP MOCNESS Plankton (MOC1) Data, 2000-2002](https://coastwatch.pfeg.noaa.gov/erddap/zh-CN/files/erdGlobecMoc1/) | MOCNESS（Multiple Opening/Closing Net and Environmental Sensing System）是一种用于收集不同深度的浮游生物样本的系统。通过MOC1设备，研究人员能够获取分层的浮游生物数据，包括生物量、物种组成和丰度等关键信息。 |
| [Image dataset of common benthic foraminifera in surface sediments of the North Atlantic Ocean](https://doi.org/10.1016/j.dib.2019.104554) |     在26个抓取站收集的表层沉积物中106个底栖有孔虫分类群      |



