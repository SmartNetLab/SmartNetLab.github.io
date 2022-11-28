# SmartNetLab.github.io

## 访问页面https://smartnetlab.github.io/

## 使用教程

1. 准备工作：本站点基于mkdocs建立，使用前需要安装mkdocs，非常简单，可参考https://blog.csdn.net/weixin_44633882/article/details/115933147 。
2. mkdocs项目（mkdocs支持markdown语法，使用方便）
3. 在github中，克隆名为SourceFile仓库，在下载的本地的docs文件中进行笔记更新，若在左侧增加了新的目录结构，需要在mkdocs.yml文件中进行添加相关配置，参考已经配置的目录即可。
4. 笔记更新完成后，执行mkdocs build命令，会自动生成site文件夹，对生成对应的html文件，将更新后的html文件与配置文件mkdocs.yml更新到GitHub的SmartNetLab.github.io仓库即可（更新后需要等待大概一分钟时间，页面https://smartnetlab.github.io/）  才会更新。
5. ```
   pip install mkdocs
   pip install mkdocs-material
   mkdocs serve
   mkdocs build
   ```

## 注意：

1. 站点使用了专为Mkdocs打造的Material模板，有很多样式，可以在mkdocs.yml中进行配置修改，在mkdocs.yml文件中已经给出一部分。在push之后需要将添加的笔记在配置文件 nav 部分里添加相关配置，具体可以参考已经给出的配置。

2. 后续会实现直接在SmartNetLab.github.io仓库上传markdown文件到对应位置，GitHub自动编译部署发布网页，而不用在下载源文件，更改源文件上传编译之后的文件（目前还实现不出来）。
