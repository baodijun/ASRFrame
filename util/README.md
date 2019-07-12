# 关于路径下几个字典的介绍
路径./util/dicts下存放了几个字典

- muti_dict.txt是ASRT_SpeechRecogonation项目中的字典，基本包含了所有的拼音，可以用来训练声学模型
- common_mnpy.txt是一个项目中统计出来的最常用的注音，用来给汉字标注拼音，可以用来训练语言模型
- pure_py.txt是我根据common_mnpy.txt统计出的拼音，又添加了下载的5个数据集中的一些拼音（太罕见的我选择的方式是把数据去掉...）
- dataset_chs.txt是根据语料中出现的汉字统计出的汉字，共6331个（去掉了特殊字符，包括 `!"'(),.?@q~“”…　、。」！（），？Ａａｂｃｋｔ`）

