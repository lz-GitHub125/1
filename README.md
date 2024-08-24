# awesome-seafloor-dataset-method
## 我们的海底调研工作

**Seafloor海底数据集研究综述** 海底数据集在海洋研究中具有重要意义。通过分析这些数据，我们可以深入了解海底地形、海洋生物分布以及环境变化等方面的信息。主要的数据集来源包括GEBCO、NOAA和SRTM等，它们提供了高分辨率的全球海底地形数据以及海洋水文和气象数据。

---

根据海洋环境特征，我们可以将海洋数据分为水文数据、地质数据和生物数据等几大类。

> 水文数据：盐度、温度、浊度
>
> 地质数据：海底地形、沉积物组成、海底地壳活动
>
> 生物数据：浮游植物、浮游动物、鱼类以及其他海洋生物

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
