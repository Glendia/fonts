# 一个免费的在线字体CDN
## 托管地址：  
```hmtl
https://fonts.workstatic.cn/
```
## 使用方式
 1. 全部调用
```html
<link rel="stylesheet" href="https://fonts.workstatic.cn/fonts/css/fonts.css" />
```
此地址包含所有字体文件，全部加载，具体方式请看文件内格式  
2. 单字体调用
```html
<link rel="stylesheet" href="https://fonts.workstatic.cn/fonts/css/fontname.css" />
```
比如：钉钉进步体
```html
<link rel="stylesheet" href="https://fonts.workstatic.cn/fonts/css/DingTalk.css" />
```
3. 本地调用
自己编写css文件，地址为字体文件链接
```css
@font-face {
    font-family: 'PingFang SC';
    src: url('https://fonts.workstatic.cn/PingFangSC/woff2/PingFangSC-Regular.woff2') format(woff2);
    font-weight: normal;
    font-style: normal;
}
```
自己编写字体css文件，远程调用字体文件即可。

## 贡献
1. 克隆仓库
```
git clone https://github.com/workstatic/fonts.git
```
2. 添加字体
3. 提交
4. 提PR
5. 提交成功后，等待审核
6. 恭喜，字体添加成功
7. 添加成功后，请到README.md文件内添加字体信息
后续可远程调用字体或者下载字体都可以。
## 字体列表
| 字体名称 | 字体文件 | 字体文件大小 | 字体文件格式 |
| :--- | :--- | :--- | :--- |
| PingFang SC | [PingFangSC-Regular.woff2](https://fonts.workstatic.cn/PingFangSC/woff2/PingFangSC-Regular.woff2) | 1.02KB | woff2 |
| PingFang SC | [PingFangSC-Medium.woff2](https://fonts.workstatic.cn/PingFangSC/woff2/PingFangSC-Medium.woff2) | 1.02KB | woff2 |
| PingFang SC | [PingFangSC-Light.woff2](https://fonts.workstatic.cn/PingFangSC/woff2/PingFangSC-Light.woff2) | 1.02KB | woff2 |
| PingFang SC | [PingFangSC-Thin.woff2](https://fonts.workstatic.cn/PingFangSC/woff2/PingFangSC-Thin.woff2) | 1.02KB | woff2 |
| PingFang SC | [PingFangSC-Semibold.woff2](https://fonts.workstatic.cn/PingFangSC/woff2/PingFangSC-Semibold.woff2) | 1.02KB | woff2 |
| PingFang SC | [PingFangSC-Ultralight.woff2](https://fonts.workstatic.cn/PingFangSC/woff2/PingFangSC-Ultralight.woff2) | 1.02KB | woff2 |
