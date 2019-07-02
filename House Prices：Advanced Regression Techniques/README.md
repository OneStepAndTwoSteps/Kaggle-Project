## 房价预测

### 文件说明

train.csv - 训练集

test.csv - 测试集

data_description.txt - 每列的完整描述，最初由Dean De Cock准备，但经过轻微编辑以匹配此处使用的列名称

sample_submission.csv - 来自销售年份和月份的线性回归的基准提交，批量平方英尺和卧室数量

### 数据字段

这是您在数据描述文件中找到的简要版本。

SalePrice - 该物业的销售价格以美元计算。这是您尝试预测的目标变量。

MSSubClass：建筑类

MSZoning：一般分区分类

LotFrontage：街道的线性脚连接到财产

LotArea：地块尺寸，平方英尺

Street：道路通道的类型

Alley：胡同通道的类型

LotShape：一般的财产形状

LandContour：物业的平整度

Utilities：可用的实用程序类型

LotConfig：批量配置

LandSlope：物业坡度

Neighborhood：Ames市区内的物理位置

Condition1：靠近主要道路或铁路

Condition2：靠近主要道路或铁路（如果存在第二个）

BldgType：住宅类型

HouseStyle：住宅风格

OverallQual：整体材料和成品质量

OverallCond：总体状况评级

YearBuilt：原始施工日期

YearRemodAdd：改造日期

RoofStyle：屋顶类型

RoofMatl：屋顶材料

Exterior1st：房屋外墙

Exterior2nd：房屋外墙（如果有多种材料）

MasVnrType：砌体贴面类型

MasVnrArea：平方英尺的砌体饰面区域

ExterQual：外部材料质量

ExterCond：外部材料的现状

Foundation：基础类型

BsmtQual：地下室的高度

BsmtCond：地下室的一般情况

BsmtExposure：罢工或花园层地下室墙壁

BsmtFinType1：地下室成品区的质量

BsmtFinSF1：类型1完成平方英尺

BsmtFinType2：第二个完成区域的质量（如果存在）

BsmtFinSF2：2型成品平方英尺

BsmtUnfSF：未完成的地下室平方英尺

TotalBsmtSF：地下室总面积

Heating：加热类型

HeatingQC：加热质量和条件

CentralAir：中央空调

Electrical：电气系统

1stFlrSF：一楼平方英尺

2ndFlrSF：二楼平方英尺

LowQualFinSF：低质量的平方英尺（所有楼层）

GrLivArea：以上（地面）生活区平方英尺

BsmtFullBath：地下室齐全的浴室

BsmtHalfBath：地下室半浴室

FullBath：满级以上的浴室

HalfBath：半年级以上

Bedroom：地下室以上的卧室数量

Kitchen：厨房数量

KitchenQual：厨房质量

TotRmsAbvGrd：以上级别的房间总数（不包括浴室）

Functional：家庭功能评级

Fireplaces：壁炉数量

FireplaceQu：壁炉质量

GarageType：车库位置

GarageYrBlt：年车库建成

GarageFinish：车库的内部装饰

GarageCars：车库容量的车库大小

GarageArea：车库的面积，平方英尺

GarageQual：车库质量

GarageCond：车库状况

PavedDrive：铺好的车道

WoodDeckSF：平方英尺的木甲板面积

OpenPorchSF：平方英尺的开放式门廊区域

EnclosedPorch：封闭的门廊面积，平方英尺

3SsnPorch：三个季节的门廊面积，平方英尺

ScreenPorch：屏幕门廊面积，平方英尺

PoolArea：泳池面积，平方英尺

PoolQC：泳池质量

Fence：栅栏质量

MiscFeature：其他类别未涵盖的其他功能

MiscVal：$杂项功能的价值

MoSold：已售出月份

YrSold：已售出年份

SaleType：销售类型

SaleCondition：销售条件