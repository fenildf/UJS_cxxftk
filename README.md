# ujs_cxxftk
- 功能：抓创新学分题库，自动答题并提交
- 适用于2017全江苏省使用该系统答题的学校
## 用法
- 安装requests模块
- 修改config.py的配置（不同学校有不同的地址、开始学号、结束学号、间隔时间）
```bash
python3 dati.py
```
- 如果提示getdict.py出现问题，请运行download.py重新下载题库，不能解决请提交issues。
- 如果出现error，请ctrl+c手动暂停脚本，并登陆后到该error地址提交一下答案，否则该题没分。
## TODO
- <del>自动答题</del> 已完成
- <del>download.py有缺陷，题库有问题</del> 已修复
