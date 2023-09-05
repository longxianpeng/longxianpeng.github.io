---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


教育经历
======
------
* <div id="expand-box-header"></div>
    <span style="float: left; font-weight: bold">同济大学</span> 
    <span style="float: right;">2021年09月 - 2024年03月</span><br>
    <span style="float: left">应用经济学&nbsp;&nbsp;硕士&nbsp;&nbsp;区域经济学</span> 
    <span style="float: right;">上海</span><br>

* <div id="expand-box-header"></div>
    <span style="float: left; font-weight: bold">中国科学技术大学</span> 
    <span style="float: right;">2015年09月 - 2019年06月</span><br>
    <span style="float: left">工学&nbsp;&nbsp;学士&nbsp;&nbsp;计算机科学与技术</span> 
    <span style="float: right;">安徽，合肥</span><br>


工作经历
======
------
* <div id="expand-box-header"></div>
    <span style="float: left; font-weight: bold">深圳字节跳动科技有限公司</span> 
    <span style="float: right;">2019年07月 - 2020年04月</span><br>
    <span style="float: left">产品与工程架构部&nbsp;&nbsp;研发工程师</span> 
    <span style="float: right;">广东，深圳</span><br>
  * 主要职责：负责字节跳动海量大规模分布式对象存储系统TOS的研发工作，为包括Tiktok、抖音、今日头条等全球产品线提供统一的非结构化数据存储和数据治理服务；
  * 重点工作：参与字节跳动第二代云存储系统TOS2.0、字节跳动第一代边缘计算与边缘存储系统的研发工作，为抖音春晚活动提供大流量挑战下的解决方案；参与字节跳动云存储的私有产品化过程（现火山引擎）；主导了基于深度学习的主动热点对象预测的高速 SSD 缓存系统的研发工作；


* <div id="expand-box-header"></div>
    <span style="float: left; font-weight: bold">广西南宁市发展与改革委员会</span> 
    <span style="float: right;">2022年07月 - 2022年08月</span><br>
    <span style="float: left">经贸与区域开放科&nbsp;&nbsp;行政助理</span> 
    <span style="float: right;">广西，南宁</span><br>
  * 日常工作：负责科室日常办文、办会及内外相关业务工作承办；
  * 重点任务：参与南宁市对外开放平台资源整合、南宁市临空经济示范区物流产业规划相关课题调研、南宁市“促消费”相关政策制定研讨工作，并形成相关调研报告及政策建议文件；


校园经历
======
------
* 荣誉奖项
  * 同济大学优秀学生
  * 同济大学优秀硕士生奖学金
  * 同济大学经济与管理学院优秀共青团员

* 学生活动
  * 同济大学经济与管理学院研究生会执行主席
  * 同济大学经济与管理学院学生委员会委员
  * 同济大学第28届研究生代表大会常任代表
  * 同济大学第28届研究生代表大会代表
 
学术成果
======
------
* 论文发表
<ul>{% for post in site.publications %}
{% include archive-single-cv.html %}
{% endfor %}</ul>

* 学术工作
  * 担任国际学术期刊《SCIENTIFIC REPORTS》审稿人，Nature子刊，SCI二区，影响因子4.9
  * 担任国际学术期刊《POLISH JOURNAL OF ENVIRONMENTAL STUDIES》审稿人，SCI四区，影响因子1.8
  * 受邀参加第十四届中国空间经济学年会，并发表《授人以鱼不如授人以渔——农村电商与农业产业组织》主题演讲

项目经历
======




1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

IS Right?
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
