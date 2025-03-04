# 规格书生成器

这是一个用于生成RVS照明产品规格书的Web应用程序。

## 功能特点

- 简单易用的界面
- 支持上传配件图和配光曲线图
- 支持编辑产品规格信息
- 一键导出规格书为PDF

## 本地运行

1. 安装依赖：

```bash
pip install -r requirements.txt
```

2. 运行应用：

```bash
python app.py
```

3. 在浏览器中访问：`http://127.0.0.1:5000`

## Vercel部署

1. 将代码推送到GitHub仓库

2. 在Vercel上创建新项目，并连接到GitHub仓库

3. 部署设置：
   - 框架预设：Other
   - 构建命令：留空
   - 输出目录：留空
   - 安装命令：`pip install -r requirements.txt`

4. 点击"部署"按钮

## 使用说明

1. 填写产品规格信息
2. 上传配件图和配光曲线图
3. 点击"导出规格书"按钮生成PDF

## 注意事项

- 图片上传大小限制为5MB
- 支持主流浏览器（Chrome、Firefox、Edge等）
- 移动设备上也可以使用 