# IK-AnalyzerByAlltuu-2012FF
* 根据项目需求，所有单个中文字符，都将其视为一个词进行输出用于建立单字索引.  
* 另外判断该字是否为词前缀进行二次成词匹配输出.  
* 修改的代码在在org.wltea.analyzer.core.CJKSegmenter.analyze(AnalyzeContext context)方法中.  
* 如需改动可根据具体业务自行修改.
