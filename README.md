# draw.io
画图

- 每一个项目作为一个目录
- 项目的不同目录也有目录
- 每一篇文章做一个目录
- 每一张图都是一个小项目
  - 方便修改
  - 方便导出为一张 png
  - 格式为 1）1.1-1.draw.io
    - 1）：表示是哪篇文章
    - 1.1：表示是文章中的哪小节
    - -1：表示是该小节的第几张图片
  - 缺点：如果项目中图片名称要改的话还需要改 draw.io 项目的名称 
 

```text
|─DailyStudy                            # 【项目】 日常学习 
  |─miscellaneous_remarks                 # 【项目中的目录】 杂谈：包括一些文章和博文
      |-essay                                 # 【目录中的目录】 文章
          |-cloud_native                          # 【目录中的目录】 云原生
            |-xx文章xx图.draw.io                    # 文章中的图  
          |-go_basic                             
          |-go_super                               
          |-three_mintue                         
          |-virtualization                        
```
