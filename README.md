# marp_theme
根据清华模板修改的自用 Marp 模板

## 如何使用

1. 下载 VS code
2. 在插件中心安装 Marp for VS Code
3. 新建一个 md 文件,复制 1~51 行 CSS 或者从该模板中直接新建。
4. 点击 1 可以实时显示 Slides,点击 2 选择 export 可以导出 PDF。
![w:10cm](https://cy-1256894686.cos.ap-beijing.myqcloud.com/20201129171243.png)

## slides 修改

```css
<style scoped>
section h1 {text-align: center;font-size: 80px;color:black;}
section {
  background-image:url('./fm.png');
  background-size:cover
}
footer{color:black;font-size: 20px;} 
</style>
<!-- _class: lead gaia -->

# Marp Slides 

---
<style >

section{
  background-image:url('./bg.png');
  background-size:cover;
  position: absolute;
  }
section h1 {font-size:40px;color:black;margin-top:px;}
section h2 {font-size:30px;color:black;margin-top:px;}
section p {font-size: 25px;color:black;}
section table {text-align: center;font-size: 32px;color:black;}
section a {font-size: 25px;color:black;}
li {font-size: 30px;text-align: left;}

img {
    margin-left: auto;
    margin-right:auto;
    display:block;
    margin:0 auto;
    width:25cm;
    }
</style>

<style scoped>
section h1 {font-size:60px;color:black;margin-top:px;}
li {font-size: 50px;text-align: left;}
</style>
```

## 首页修改

- 预设了适合展示的标题大小,如果需要修改适合投影的字体大小可修改`h1`的`font-size`。
- 改变`background-image:url('./fm.png');`可以修改首页背景图片。

## 背景修改

- 修改`background-image:url('./bg.png');`中背景图片即可.

## 字体修改

`h1`一级大标题
`h2`二级大标题
`p`正文字体
`table`表格字体,居中
`li`列表字体,居左

## 图片格式
默认居中,临时在某一slides中修改可以

```css
<style scoped>
img {
    margin-left: auto; margin-right:auto;
    display:block;margin:0 auto;width:25cm;
    }
</style>
或者:
![w:2cm h:2cm](fm.png)
```

## 左右排布

```
![bg right:40% w:5cm h:5cm](fm.png)
```

# CSS 说明
```
https://marpit.marp.app/theme-css
```

## 更多细节
```
https://marpit.marp.app/usage
```