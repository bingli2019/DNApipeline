# DNApipeline



## 基本用法

```
python3 DNA.py -i <yaml>
```


## 更新
20240207 重写以便于适配人，鼠物种等。

20210530 snakemake与WDL版本用于内部生产环境，不公开

20210517 着手用WDL重写

20210510 着手用snakemake重写

20210428 基本完成，着手写文档，另外或者打包成docker？或者用WDL重写？

20210415 注释模式固定为先用snpEff再用annovar，不再可选。更新中。脚本目前保留hg38的使用接口，但是鉴于hg38在很长一段时间都不会成为国内主流，因此暂停hg38部分的更新。

20210402 配对样本模式开始动工。

20210326 完整流程已跑通。

20210222 先搞一条线。

20210220 破土动工，开工大吉！
