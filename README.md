Tex templates for Zhejiang University Thesis
============

从[google code](https://code.google.com/archive/p/zjuthesistex)中抢救过来，原文件和相关文档在[downloads](downloads) ，原[wiki](ProjectHome.md)也从另一个branch中拷了过来。

## How to use

#### 全校模板
此模板由王东举制作，我直接解压了其utf8版本，并适当修改以删除新的tex环境中废弃的命令。

一般情况下，环境已经配好的情况下，修改[论文模版示例.tex](school/论文模版示例.tex)和[Chapters](school/Chapters)中的对应章节，引用添加在[thesisbib.bib](school/thesisbib.bib)，然后在[school](school)目录中运行`make`，就可以编出来 **论文模版示例.pdf**。

详细请参考[论文LaTeX版本快速指南V2.0.1.pdf](school/论文LaTeX版本快速指南V2.0.1.pdf).

#### 计算机学院本科生模板
此模板由pluskid制作，我直接copy了其[github代码](https://github.com/pluskid/cs_thesis_zju)，并适当修改以删除新的tex环境中废弃的命令。

一般情况下，在[cs_undergraduate](cs_undergraduate)目录中运行`make`，就可以编出来。

#### 计算机学院研究生模板
此模板由我(ambling)在王东举模板的基础上，结合pluskid和计算机学院的word模板，修改完成。

一般情况下，在[cs_graduate](cs_graduate)目录中运行`make`，就可以编出来。

## 相关链接
以下链接可能需要浙大内网访问。现在（2018年1月）貌似还是最新版。因为我主要用来写博士论文，所以只关注了研究生的相关规定。

1. [关于公布《浙江大学研究生学位论文编写规则》的通知](http://grs.zju.edu.cn/redir.php?catalog_id=10038&object_id=12782)
2. [CC98帖子](http://www.cc98.org/topic/4654580)
3. [研究生院学位管理文件](http://grs.zju.edu.cn/redir.php?catalog_id=10044&tag=%E5%AD%A6%E4%BD%8D%E7%AE%A1%E7%90%86)
4. [研究生院论文评审](http://grs.zju.edu.cn/redir.php?catalog_id=10039)
5. [使用latex撰写博士,硕士学位论文](http://www.cnblogs.com/tsingke/p/6358396.html)
6. [浙江大学计算机系本科生毕业论（设计）LaTeX 模板](http://blog.pluskid.org/?p=320)
7. [浙江大学计算机学院与软件学院研究生学位论文模板](http://cspo.zju.edu.cn/redir.php?catalog_id=16115&object_id=28990)
