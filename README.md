# Water-confined-density-prediction-APP
This app is a MATLAB app where researchers can predict the confined density of water in carbon nanotubes (CNT)
这是一个计算纳米受限水密度的MATLAB APP
Researchers can install this app with MATLAB software
研究者们可以通过MATLAB软件安装此APP，并进行使用
Input parameters and units: temperature (K), pressure (MPa), bulk density of water (Kg/m^3), diameter of CNT (Å), and sigmaC-O (it is optional, and the default value is 3.2865Å)
输入参数有温度（K），压力（MPa），体相水的密度（Kg/m^3，可以查阅相关的实验值或者在NIST上查询），纳米管的直径 (Å)，CO之间的sigma（这是一个可选的参数，默认值是3.2865Å）
It should be noted that the CNT is a single-wall CNT, and the diameter of the CNT in the input parameter is the original diameter, not the effective diameter(original diameter minus sigma_CO)
需要注意的是，纳米管是单壁纳米管，且输入参数中纳米管的直径是原始直径，而非减去sigma_CO的有效直径
The calculation equations of original diameter D and effective diameter Deff are as follows, where the default C-C bond length acc is 1.42Å
原始直径D和有效直径Deff的计算公式如下，其中C-C键长默认为1.42Å
 
Output parameters and units: confined density of water (Kg/m^3) and efficient confined density of water (Kg/m^3). For confined density of water, We do not consider the effect of excluded volume, and directly use the original diameter D to calculate the volume of CNT. For efficient confined density of water, We consider the effect of excluded volume, and use the efficient diameter Deff to calculate the volume of CNT.Researchers can choose the density value according to their own situation.
输出参数有两个，一个是受限密度，一个是有效受限密度，它们的单位都是Kg/m^3。对于受限密度，我们没有考虑排出体积的影响，直接使用了CNT的原始直径D计算了CNT的体积。对于有效受限密度，我们考虑了排出体积的影响，使用了有效直径Deff计算了CNT的体积。研究者可根据自身的情况，选择自己需要的密度值。
The best prediction range of input parameters: temperature (600-1173 K, and 300 K), pressure (20-30 MPa, and 1 atm), diameter (9.49-50.17 Å)
最佳的参数输入范围为，温度:600-1173 K，和常温300 K；压力:20-30 MPa，和常压1 atm；压力:20-30 MPa，和常压1 atm；CNT管径：9.49-50.17 Å
The origin MD data can be found in excel file
原始的分子模拟MD数据，已经以excel文件形式放置在了文件夹中
If you have any questions, please contact zbwxjtu@163.com
如果您有任何问题，请联系邮箱zbwxjtu@163.com
