# Vue-cli-plugin-svg-icon

> Svg-icon的插件，无需配置webpack，直接使用组件

## 安装

```javascript
$ vue add svg-icon
```

## 使用

无需配置`webpack`，可以直接在项目中使用组件，该插件自动配置好了`webpack`，在src的assets目录中生成icons文件夹，使用中只需要把svg文件放入icons的svg文件夹里面统一管理

在项目中使用svgIcon组件

```
<svg-icon icon-class="fontName" className="className"/>
```

## 参数

| 参数       | 说明        | 类型   | 默认值 | 是否必须 |
| ---------- | ----------- | ------ | ------ | -------- |
| icon-class | 图标的名字  | String | 无     | 是       |
| className  | 图标的class | String | ''     | 否       |

## 优化

初始安装插件的时候有对话是否选择用[svgo](https://github.com/svg/svgo)对svg文件进行优化，比如去除一些无用的注释。