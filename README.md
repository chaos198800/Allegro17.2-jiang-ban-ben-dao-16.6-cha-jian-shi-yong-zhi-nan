# Allegro 17.2 降版本到 16.6 插件使用指南

## 简介

本资源文件提供了一个用于将 Allegro 17.2 版本的 PCB 文件降版本到 16.6 版本的插件。通过使用该插件，用户可以方便地将高版本的 PCB 文件转换为低版本的格式，以便在旧版本的 Allegro 软件中继续使用。

## 使用步骤

1. **解压文件**  
   将下载的资源文件解压，并将解压后的文件放入 PCBENV 目录下。

2. **修改 allegro.ilinit 文件**  
   在 Allegro 的 allegro.ilinit 文件中添加以下代码：
   ```
   loadi(x_downrev17.il deargds)
   ```

3. **导出 17.2 版本的数据**  
   打开 17.2 版本的 PCB 文件，执行以下命令：
   ```
   Command > downrev17
   ```
   选择数据导出的目录（建议使用默认目录），然后执行导出操作。

4. **导入数据到 16.6 版本**  
   打开 Allegro 16.6 软件，执行以下命令：
   ```
   Command > downrev17
   ```
   选择上一步 17.2 版本数据导出的目录位置，然后进行导入操作。

## 注意事项

- 请确保在执行操作前备份好原始文件，以防数据丢失。
- 该插件仅适用于从 Allegro 17.2 降版本到 16.6，其他版本可能不适用。
- 如果在使用过程中遇到问题，请参考 Allegro 官方文档或联系技术支持。

## 结束语

通过本插件，您可以轻松地将 Allegro 17.2 版本的 PCB 文件降版本到 16.6 版本，方便在旧版本的软件中继续使用。希望本资源对您的工作有所帮助！

## 下载链接

[Allegro17.2降版本到16.6插件使用指南](https://pan.quark.cn/s/f35a97d27dfc)