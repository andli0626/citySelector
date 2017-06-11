# 微信小程序 城市/区县定位选择器

### 主要功能
* **自动定位** 城市、区县（也支持手动）
* 输入框内，通过 **拼音搜索** 城市，支持全拼、简拼
* 亦可通过 **侧边栏** 选择，城市按拼音首字母排列
* 选择好城市后，自动显示 **区县**

### 说明
* 使用（且小程序只能使用）腾讯地图的API
* 将utils目录中，`config.default.js`文件改名为`config.js`
* 并将其中的`key`改为自己的腾讯地图key（申请快速且免费）
* ES6
* 可 **直接作为模块使用**，如果对您有帮助，请star

![image](./citySelectorGif.gif)
