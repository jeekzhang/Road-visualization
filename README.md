# 民间道路长
### 一路低碳—骑行友好度数据可视化

该项目是阿里云码上公益项目，旨在展示道路骑行友好度的数据可视化。通过两个网页（画布）展示了相关信息。

## 画布

#### 第一张画布

第一张画布展示了道路骑行友好度的总体情况，包括以下内容：

- 道路区间总得分Top5：展示了得分排名前五的道路区间。
- 道路得分总排行：展示了所有道路得分的排行榜。
- 性质权重占比：展示了不同性质在总得分中的权重比例，按照1:4:5的比例分配。
- 机动车道路情况占比：展示了机动车道路在总体道路中的占比。
- 总体道路图片展示：展示了总体道路的图片，并根据不同得分着色。底部注明了得分对应的颜色关系。每个道路的具体得分以云朵标签的形式展示，点击即可查看详细信息。
- 地图缩放功能：支持对地图进行正常的缩放操作。
![img](https://img2023.cnblogs.com/blog/3018649/202301/3018649-20230112163717980-2139804803.jpg)

#### 第二张画布

第二张画布展示了每条具体道路的性质信息，包括以下内容：

- 道路区间得分Top5：展示了每条道路中得分排名前五的道路区间。
- 总体道路某个性质的排名Top5：展示了某个性质在所有道路中的得分排名前五。
- 道路与性质筛选功能：支持根据道路和性质进行筛选。选择道路和属性后，将显示该道路的总得分和对应属性得分，并且地图会放大到该道路，并隐藏其他道路的显示。

两张画布之间支持切换，点击"返回"按钮即可返回上一张画布。
![img](https://img2023.cnblogs.com/blog/3018649/202301/3018649-20230112163718481-172652676.jpg)

## 项目使用
项目链接：www.mjdlz.cn

该项目是一个数据可视化的网页应用，你可以将其部署在任何支持静态网页的服务器上。为了使用该项目，你需要按照以下步骤操作：

1. fork该项目

2. 将项目文件名修改为用户名+.github.io（如mjdlz.github.io）

3. 在浏览器中访问上述网址，即可开始使用道路骑行友好度数据可视化应用。

## 技术要求

该项目使用了以下技术和工具：

- HTML、CSS、JavaScript：用于网页的结构、样式和交互逻辑。
- 阿里云码上公益项目：提供了项目的需求。
- 数据可视化库（Folium）：用于创建交互式地图的库，基于Leaflet.js。它可以生成具有缩放、平移和交互功能的地图，并支持添加标记、图层和地理数据。

## 参与贡献

如果你对该项目感兴趣，并且想要为其做出贡献，你可以按照以下步骤进行：

1. Fork该仓库到你自己的GitHub账号中。
2. 进行你的修改和改进。
3. 提交Pull请求，将你的修改合并到主仓库中进行审查和合并。

## 帮助与支持

如果你在使用该项目时遇到任何问题或有任何疑问，请随时提出问题或寻求帮助。你可以通过以下方式与我们联系：

- 提交Issue：在项目的GitHub仓库中提交问题描述。
- 联系开发者：通过[电子邮件](mailto:jeekzhang@139.com)联系我们。

感谢你的关注和参与！我们期待你的贡献，并希望该项目能够为骑行者提供有用的信息和支持。
