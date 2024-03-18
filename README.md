# KGQA-Psychological-Counseling

(原地址 作者:fumuling)[https://github.com/fumuling/KGQA-Psychological-Counseling]



## schema

#### 知识图谱实体类型

| 实体类型          | 中文含义 | 举例                                   |
| :---------------- | :------: | :------------------------------------- |
| disease           | 疾病名称 | 广泛性焦虑障碍                         |
| alternate_name    | 疾病别称 | 泛化性焦虑症, 广泛焦虑障碍, 广泛焦虑症 |
| pathogenic_site   | 病发部位 | 全身                                   |
| department        |   科室   | 精神病科, 心理咨询科                   |
| symptom           |   症状   | 心烦、头痛、坐立不安、惊恐伤肾阳痿...  |
| check             | 检查项目 | 心理咨询                               |
| susceptible_crowd | 易感人群 | 成年人                                 |

#### 知识图谱实体关系类型

| 实体关系类型            |   中文含义   | 举例                               |
| :---------------------- | :----------: | :--------------------------------- |
| disease_alternate_name  |   疾病别名   | <广泛性焦虑障碍,别称,泛化性焦虑症> |
| disease_pathogenic_site | 疾病感染部位 | <广泛性焦虑障碍,感染部位,全身>     |
| disease_symptom         |   疾病症状   | <广泛性焦虑障碍,症状,惊恐伤肾阳痿> |
| disease_check           | 疾病所需检查 | <广泛性焦虑障碍,检查,心理咨询>     |
| disease_department      | 疾病所属科室 | <广泛性焦虑障碍,科室,心理咨询科>   |
| disease_complication    |    并发症    | <广泛性焦虑障碍,并发症,强迫症>     |
| disease_confusable      |  易混淆病症  | <广泛性焦虑障碍,易混淆病症,抑郁症> |
| disease_crowd           | 疾病易感人群 | <广泛性焦虑障碍,易感人群,成年人>   |

#### 知识图谱属性类型

| 属性类型      | 中文含义 |                            举例                             |
| :------------ | :------: | :---------------------------------------------------------: |
| expert_remind | 专家建议 | 患者忌吃带有刺激性的食物和烟酒，多吃些海产品、豆类、牛奶... |
| infectivity   |  传染性  |                      该病不具有传染性                       |
| heredity      |  遗传性  |                           不遗传                            |





抽取原始数据字典中各字段的数据属性值集合，分别写入txt文件，作为问答系统中的特征词库
