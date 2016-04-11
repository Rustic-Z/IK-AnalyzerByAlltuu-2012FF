# IK-AnalyzerByAlltuu-2012FF

### 2016年4月11日 第二次更新
* 根据上下文所选的分词策略useSmart(true为智能切分,false为最细粒度切分)判断是否增加单字成词.  

### 2016年4月10 第一次更新
* 根据项目需求，所有单个中文字符，都将其视为一个词进行输出用于建立单字索引.  
* 另外判断该字是否为词前缀进行二次成词匹配输出.  
* 修改的代码在在org.wltea.analyzer.core.CJKSegmenter.analyze(AnalyzeContext context)方法中.  
* 如需改动可根据具体业务自行修改.  
