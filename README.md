
# CLiB中文大模型能力评测榜单（持续更新）
- 目前已囊括77个大模型，覆盖chatgpt、gpt4、谷歌bard、百度文心一言、阿里通义千问、讯飞星火、360智脑、商汤senseChat、微软new-bing、minimax等商用模型，
以及百川、qwen、belle、chatglm6b、tigerbot、ziya、openbuddy、Phoenix、linly、MOSS、AquilaChat、vicuna、wizardLM、书生internLM、llama2-chat等开源大模型。
- 模型来源涉及国内外大厂、大模型创业公司、高校研究机构。
- 支持多维度能力评测，包括分类能力、信息抽取能力、阅读理解能力、表格问答能力。
- 不仅提供能力评分排行榜，也提供所有模型的原始输出结果！有兴趣的朋友可以自己打分、自己排行！

## 目录
- [🔄最近更新](#最近更新)
- [⚓TODO](#todo)
- [📝大模型基本信息](#大模型基本信息)
- [📊排行榜](#-排行榜)
  - [综合能力排行榜](#1综合能力排行榜)
    - 10B以下开源大模型排行榜
    - 10B~20B开源大模型排行榜
    - 20B以上开源大模型排行榜
  - [分类能力排行榜](#2分类能力排行榜)
  - [信息抽取能力排行榜](#3信息抽取能力排行榜)
  - [阅读理解能力排行榜](#4阅读理解能力排行榜)
  - [数据分析排行榜](#5数据分析排行榜)
  - [中文编码效率排行榜](#6中文编码效率排行榜)
- [🌐各项能力评分](#🌐各项能力评分)
- [⚖️原始评测数据](#⚖️原始评测数据)
- [为什么做榜单？](#为什么做榜单)


## 最近更新
- [2024/4/13] 发布v1.16版本评测榜单
  - 新增中文编码效率排行榜，同等尺寸大模型，编码效率越高推理速度越快，几乎成正比。
  - 模型更新：minimax更新至minimax-abab6-chat
  - 新增3个大模型：Qwen1.5-32B-Chat、minimax-abab5.5-chat、minimax-abab5.5s-chat
- [2024/3/20] 发布v1.15版本评测榜单
  - 模型更新：gpt3.5更新至最新版本
  - 新增8个大模型：gpt-4-turbo、讯飞星火v3.5、MiniCPM-2B-dpo、miniCPM-2B-sft、AquilaChat2-70B-Expr、月之暗面kimichat、谷歌gemma-7b-it、谷歌gemma-2b-it
  - 排行榜删除陈旧的模型（比如Baichuan2-53B、chatglm-130b-v1、tulu-30b、belle-llama-13b-2m、belle-llama-13b-ext、openbuddy-llama-30b-v7.1、vicuna-33b等）
- [2024/2/28] 发布v1.14版本评测榜单
  - 新增11个大模型：deepseek-llm-67b-chat、baichuan3、internlm2-chat-20b、internlm2-chat-7b、openbuddy-mixtral-7bx8-v17.1以及qwen1.5系列的6个模型
  - 排行榜删除陈旧的模型（比如chatglm2-6b、AquilaChat-7B等）
- [2024/1/29] 发布v1.13版本评测榜单
  - 模型更新：微软new-bing、文心4.0更新至24年1月版本
  - 新增6个大模型：qwen-max、GLM4、BlueLM-7B-Chat、openbuddy-zephyr-7b-v14.1、openbuddy-deepseek-67b-v15.2、XVERSE-65B-Chat
  - 排行榜删除陈旧的模型（比如phoenix-inst-chat-7b、BELLE-on-Open-Datasets等）
- [2023/12/10] 发布v1.12版本评测榜单
  - 新增7个大模型：Yi-34B-Chat、tigerbot-13b-chat-v4、openbuddy-openllama-3b-v10、Qwen-1_8B-Chat、Yi-6B-Chat、Qwen-72B-Chat、chatglm-turbo
  - 新增开源模型细分排行榜：10B以下模型排行榜、10B~20B模型排行榜、20B以上模型排行榜
- [2023/11/22] 发布v1.11版本评测榜单
  - 新增4个大模型：openbuddy-mistral-7b-v13.1、Qwen-7B-Chat、Baichuan2-7B-Chat、tigerbot-70b-chat-v3
  - 将数据分析能力计入综合得分
- [2023/11/5] 发布v1.10版本评测榜单
  - 新增6个大模型：
    - 3个商用模型：文心4.0、谷歌bard、讯飞星火v3
    - 3个开源模型：aquilachat2-34b、ziya2-13b-chat、chatglm3-6b
  - 排行榜删除陈旧的模型（比如第一代chatglm-6b、MOSS等）
- [2023/10/11] 发布v1.9版本评测榜单
  - 新增7个大模型：
    - 3个商用模型：阿里通义千问v1.0.7、豆包、Baichuan2-53B
    - 4个开源模型：Baichuan2-13B-Chat、internlm-chat-20b、qwen-14b-chat、tigerbot-70b-chat-v2
- [2023/9/13] 发布v1.8版本评测榜单
  - 新增7个大模型：
    - 2个商用模型：chatglm-std、chatglm-pro
    - 5个开源模型：openbuddy-llama-30b-v7.1、openbuddy-llama-65b-v8、openbuddy-llama2-70b-v10.1、xverse-13b-chat、Baichuan-13B-Chat-v2
- [2023/8/29] 发布v1.7版本评测榜单
  - 新增2个商用大模型：讯飞星火v2.0、Baichuan-53B
  - 表格问答（数据分析）能力排行榜：新增21个模型参与排行。
- [2023/8/13] 发布v1.6版本评测榜单，[link](https://github.com/jeinlee1991/chinese-llm-benchmark/releases/tag/v1.6)
  - 新增4个大模型：
    - 2个商用模型：商汤senseChat、微软new-bing
    - 2个基于LLaMA2的开源中文模型：BELLE-Llama2-13B-chat-0.4M、Linly-Chinese-LLaMA2-13B
- [2023/7/26] 发布v1.5版本评测榜单，[link](https://github.com/jeinlee1991/chinese-llm-benchmark/releases/tag/v1.5)
  - 新增7个大模型：gpt4、文心一言v2.2、vicuna-33b、wizardlm-13b、Ziya-LLaMA-13B-v1.1、InternLM-Chat-7B、Llama-2-70b-chat
- [2023/7/18] 发布v1.4版本评测榜单，[link](https://github.com/jeinlee1991/chinese-llm-benchmark/releases/tag/v1.4)
  - 新增3个大模型：tulu-30b、chatglm2-6b、Baichuan-13B-Chat
- [2023/7/2] 发布v1.3版本评测榜单，[link](https://github.com/jeinlee1991/chinese-llm-benchmark/releases/tag/v1.3)
  - 新增3个大模型：360智脑、MOSS-003-SFT、AquilaChat-7B
  - 讯飞星火更新为最新的v1.5模型
- [2023/6/17] 发布v1.2版本评测榜单，[link](https://github.com/jeinlee1991/chinese-llm-benchmark/releases/tag/v1.2)
  - 新增2个大模型：tigetbot-7b官网、linly-chatflow-13b
  - 说明做评测榜单的初衷
- [2023/6/10] 发布v1.1版本评测榜单，[link](https://github.com/jeinlee1991/chinese-llm-benchmark/releases/tag/v1.1)
  - 新增3个大模型：minimax、guanaco、Phoenix-7b
  - 新增表格问答评测维度，作为阅读理解能力的细分项
- [2023/6/4] 发布v1版本评测榜单，[link](https://github.com/jeinlee1991/chinese-llm-benchmark/releases/tag/v1.0)

## TODO
- 将更多大模型加入评测：Claude、falcon等等
- 增加开源大模型的授权协议，注明能否商用
- 引入更多维度的评测：数学能力、代码能力、开放域问答、多轮对话、头脑风暴、翻译……
- 评测维度更细分，比如信息抽取可以细分时间实体抽取能力、地址实体抽取能力……
- 海纳百川，整合各类评测榜单，扩充细分领域榜单（比如教育领域、医疗领域）
- 加入更多评测数据，使得评测得分越来越有说服力

## 大模型基本信息
详见 [中文大模型资源汇总（商用及开源）](https://github.com/jeinlee1991/chinese-llm-benchmark/blob/main/LLM-info.md)

## 📊 排行榜
### 1、综合能力排行榜
综合能力得分为分类能力、信息抽取能力、阅读理解能力、数据分析能力四者得分的平均值。
![lin](pic/total.png)

| 类别 | 大模型                         | 总分  | 排名 |
|-----|------------------------------|------|----|
|商用|gpt4|96.1|1|
|商用|微软new-bing|93.0|2|
|商用|gpt-4-turbo|92.8|3|
|商用|GLM4|92.3|4|
|商用|文心4.0|91.4|5|
|商用|minimax-abab6-chat(new)|90.3|6|
|开源|Qwen1.5-32B-Chat(new)|89.3|7|
|商用|讯飞星火v3.5|88.9|8|
|商用|阿里qwen-max|88.7|9|
|商用|月之暗面kimichat|87.6|10|
|开源|Qwen1.5-14B-Chat|87.3|11|
|开源|Qwen-72B-Chat|87.3|12|
|开源|Qwen1.5-72B-Chat|87.1|13|
|商用|gpt-3.5-turbo|87.0|14|
|开源|internlm2-chat-20b|86.8|15|
|开源|AquilaChat2-70B-Expr|86.8|16|
|开源|deepseek-llm-67b-chat|86.7|17|
|商用|文心一言v2.2|86.5|18|
|开源|tigerbot-70b-chat-v2|86.5|19|
|开源|openbuddy-deepseek-67b|86.2|20|
|商用|baichuan3|86.1|21|
|商用|讯飞星火v3|85.8|22|
|开源|XVERSE-65B-Chat|85.0|23|
|商用|谷歌bard|84.1|24|
|开源|tigerbot-70b-chat-v3|83.5|25|
|开源|openbuddy-llama2-70b-v10.1|83.2|26|
|商用|chatglm-turbo|83.0|27|
|开源|tigerbot-13b-chat-v4|83.0|28|
|开源|Yi-34B-Chat|82.9|29|
|开源|aquilachat2-34b|82.5|30|
|商用|商汤senseChat|81.9|31|
|开源|openbuddy-mixtral-7bx8-v17.1|81.8|32|
|开源|internlm2-chat-7b|80.6|33|
|商用|minimax-abab5.5-chat(new)|80.3|34|
|开源|BELLE-Llama2-13B-chat-0.4M|79.8|35|
|商用|字节跳动豆包|79.5|36|
|开源|Baichuan2-13B-Chat|79.4|37|
|开源|qwen-14b-chat|79.4|38|
|开源|Baichuan2-7B-Chat|79.1|39|
|商用|阿里通义千问|79.0|40|
|开源|openbuddy-zephyr-7b|77.8|41|
|开源|BlueLM-7B-Chat|77.8|42|
|开源|openbuddy-llama-65b-v8|76.8|43|
|开源|xverse-13b-chat|76.6|44|
|商用|chatglm-std|76.0|45|
|商用|chatglm-pro|75.8|46|
|开源|Qwen1.5-7B-Chat|75.7|47|
|商用|讯飞星火v1.5|75.5|48|
|开源|谷歌gemma-7b-it|75.3|49|
|开源|openbuddy-mistral-7b-v13.1|75.1|50|
|商用|360智脑|74.3|51|
|开源|MiniCPM-2B-dpo|74.0|52|
|开源|Llama-2-70b-chat|73.6|53|
|开源|Qwen-7B-Chat|73.5|54|
|商用|讯飞星火v2.0|72.8|55|
|开源|Baichuan-13B-Chat-v2|72.7|56|
|开源|chatglm3-6b|72.2|57|
|开源|Qwen1.5-4B-Chat|70.6|58|
|开源|miniCPM-2B-sft|68.7|59|
|开源|Yi-6B-Chat|68.7|60|
|开源|ziya2-13b-chat|67.3|61|
|开源|Linly-Chinese-LLaMA2-13B|67.3|62|
|开源|Qwen-1_8B-Chat|66.4|63|
|商用|minimax-abab5.5s-chat(new)|60.4|64|
|开源|openbuddy-openllama-3b-v10|56.5|65|
|开源|谷歌gemma-2b-it|54.8|66|
|开源|Qwen1.5-1.8B-Chat|53.9|67|
|开源|Qwen1.5-0.5B-Chat|44.7|68|

<br>

#### (1) 10B以下大模型排行榜
| 类别 | 大模型                        | 分类能力 | 信息抽取能力 | 阅读理解能力 | 表格问答 | 总分   | 排名 |
|----|----------------------------|------|--------|--------|------|------|----|
|开源|internlm2-chat-7b|86|81|72.7|82.7|80.6|1|
|开源|Baichuan2-7B-Chat|88|76|83.3|69.0|79.1|2|
|开源|openbuddy-zephyr-7b|82|83|74.0|72.0|77.8|3|
|开源|BlueLM-7B-Chat|82|83|74.0|72.0|77.8|4|
|开源|Qwen1.5-7B-Chat|80|76|76.0|70.7|75.7|5|
|开源|谷歌gemma-7b-it|72|79|74.0|76.0|75.3|6|
|开源|openbuddy-mistral-7b-v13.1|79|72|73.3|76.0|75.1|7|
|开源|MiniCPM-2B-dpo|79|77|74.0|66.0|74.0|8|
|开源|Qwen-7B-Chat|89|72|74.0|59.0|73.5|9|
|开源|chatglm3-6b|82|68|78.7|60.0|72.2|10|
|开源|Qwen1.5-4B-Chat|75|65|79.3|63.0|70.6|11|
|开源|miniCPM-2B-sft|72|72|77.3|53.3|68.7|12|
|开源|Yi-6B-Chat|73|71|66.0|64.7|68.7|13|
|开源|Qwen-1_8B-Chat|73|66|75.3|51.3|66.4|14|
|开源|openbuddy-openllama-3b-v10|64|60|61.3|40.7|56.5|15|
|开源|谷歌gemma-2b-it|56|60|60.0|43.3|54.8|16|
|开源|Qwen1.5-1.8B-Chat|57|58|52.7|48.0|53.9|17|
|开源|Qwen1.5-0.5B-Chat|44|40|60.0|34.7|44.7|18|

<br>

#### (2) 10B~20B大模型排行榜
| 类别 | 大模型                        | 分类能力 | 信息抽取能力 | 阅读理解能力 | 表格问答 | 总分   | 排名 |
|----|----------------------------|------|--------|--------|------|------|----|
|开源|Qwen1.5-14B-Chat|89|79|90.7|90.7|87.3|1|
|开源|internlm2-chat-20b|93|80|86.0|88.0|86.8|2|
|开源|tigerbot-13b-chat-v4|85|82|80.0|85.0|83.0|3|
|开源|BELLE-Llama2-13B-chat-0.4M|90|74|76.0|79.0|79.8|4|
|开源|Baichuan2-13B-Chat|83|83|74.7|77.0|79.4|5|
|开源|qwen-14b-chat|84|72|84.7|77.0|79.4|6|
|开源|xverse-13b-chat|86|72|81.3|67.0|76.6|7|
|开源|Baichuan-13B-Chat-v2|82|69|72.7|67.0|72.7|8|
|开源|ziya2-13b-chat|76|54|71.3|68.0|67.3|9|
|开源|Linly-Chinese-LLaMA2-13B|78|67|67.3|57.0|67.3|10|

<br>

#### (3) 30B以上大模型排行榜
| 类别 | 大模型                          | 分类能力 | 信息抽取能力 | 阅读理解能力 | 表格问答 | 总分   | 排名 |
|----|------------------------------|------|--------|--------|------|------|----|
|开源|Qwen1.5-32B-Chat(new)|91|86|92.7|87.3|89.3|1|
|开源|Qwen-72B-Chat|89|80|92.7|87.3|87.3|2|
|开源|Qwen1.5-72B-Chat|89|84|88.0|87.3|87.1|3|
|开源|AquilaChat2-70B-Expr|82|84|92.0|89.3|86.8|4|
|开源|deepseek-llm-67b-chat|87|81|86.7|92.0|86.7|5|
|开源|tigerbot-70b-chat-v2|97|84|80.0|85.0|86.5|6|
|开源|openbuddy-deepseek-67b|86|89|84.7|85.0|86.2|7|
|开源|XVERSE-65B-Chat|83|84|84.0|89.0|85.0|8|
|开源|tigerbot-70b-chat-v3|94|85|84.0|71.0|83.5|9|
|开源|openbuddy-llama2-70b-v10.1|86|84|86.7|76.0|83.2|10|
|开源|Yi-34B-Chat|88|82|84.7|77.0|82.9|11|
|开源|aquilachat2-34b|77|82|88.0|83.0|82.5|12|
|开源|openbuddy-mixtral-7bx8-v17.1|86|73|86.0|82.0|81.8|13|
|开源|openbuddy-llama-65b-v8|68|84|79.3|76.0|76.8|14|
|开源|Llama-2-70b-chat|86|66|73.3|69.0|73.6|15|

<br>

### 2、分类能力排行榜
![lin](pic/classification.png)

| 类别| 大模型                         | 分类能力 | 排名 |
|---|-----------------------------|------|----|
|开源|tigerbot-70b-chat-v2|97|1|
|商用|微软new-bing|95|2|
|商用|gpt4|94|3|
|开源|tigerbot-70b-chat-v3|94|4|
|开源|internlm2-chat-20b|93|5|
|商用|月之暗面kimichat|92|6|
|开源|Qwen1.5-32B-Chat(new)|91|7|
|商用|gpt-4-turbo|91|8|
|开源|BELLE-Llama2-13B-chat-0.4M|90|9|
|商用|文心一言v2.2|90|10|
|开源|Qwen1.5-14B-Chat|89|11|
|开源|Qwen-7B-Chat|89|12|
|开源|Qwen-72B-Chat|89|13|
|开源|Qwen1.5-72B-Chat|89|14|
|开源|Yi-34B-Chat|88|15|
|开源|Baichuan2-7B-Chat|88|16|
|商用|文心4.0|88|17|
|商用|讯飞星火v3.5|87|18|
|商用|minimax-abab6-chat(new)|87|19|
|商用|讯飞星火v3|87|20|
|开源|deepseek-llm-67b-chat|87|21|
|开源|Llama-2-70b-chat|86|22|
|开源|xverse-13b-chat|86|23|
|开源|openbuddy-mixtral-7bx8-v17.1|86|24|
|商用|GLM4|86|25|
|商用|360智脑|86|26|
|商用|chatglm-turbo|86|27|
|开源|openbuddy-deepseek-67b|86|28|
|开源|internlm2-chat-7b|86|29|
|商用|谷歌bard|86|30|
|商用|阿里qwen-max|86|31|
|商用|baichuan3|86|32|
|开源|openbuddy-llama2-70b-v10.1|86|33|
|开源|tigerbot-13b-chat-v4|85|34|
|开源|qwen-14b-chat|84|35|
|商用|chatglm-pro|84|36|
|商用|chatglm-std|84|37|
|开源|XVERSE-65B-Chat|83|38|
|商用|minimax-abab5.5-chat(new)|83|39|
|开源|Baichuan2-13B-Chat|83|40|
|开源|AquilaChat2-70B-Expr|82|41|
|开源|Baichuan-13B-Chat-v2|82|42|
|开源|chatglm3-6b|82|43|
|开源|openbuddy-zephyr-7b|82|44|
|开源|BlueLM-7B-Chat|82|45|
|商用|商汤senseChat|82|46|
|商用|gpt-3.5-turbo|81|47|
|商用|阿里通义千问|81|48|
|开源|Qwen1.5-7B-Chat|80|49|
|开源|openbuddy-mistral-7b-v13.1|79|50|
|商用|字节跳动豆包|79|51|
|开源|MiniCPM-2B-dpo|79|52|
|开源|Linly-Chinese-LLaMA2-13B|78|53|
|开源|aquilachat2-34b|77|54|
|商用|讯飞星火v1.5|76|55|
|开源|ziya2-13b-chat|76|56|
|开源|Qwen1.5-4B-Chat|75|57|
|开源|Qwen-1_8B-Chat|73|58|
|开源|Yi-6B-Chat|73|59|
|开源|miniCPM-2B-sft|72|60|
|开源|谷歌gemma-7b-it|72|61|
|商用|讯飞星火v2.0|72|62|
|开源|openbuddy-llama-65b-v8|68|63|
|开源|openbuddy-openllama-3b-v10|64|64|
|商用|minimax-abab5.5s-chat(new)|58|65|
|开源|Qwen1.5-1.8B-Chat|57|66|
|开源|谷歌gemma-2b-it|56|67|
|开源|Qwen1.5-0.5B-Chat|44|68|

<br>

### 3、信息抽取能力排行榜
![lin](pic/extract.png)

| 类别| 大模型                         | 信息抽取能力 | 排名 |
|---|-----------------------------|--------|----|
|商用|gpt4|94|1|
|商用|讯飞星火v3.5|92|2|
|商用|GLM4|90|3|
|商用|gpt-4-turbo|90|4|
|商用|文心4.0|89|5|
|开源|openbuddy-deepseek-67b|89|6|
|商用|谷歌bard|88|7|
|商用|文心一言v2.2|87|8|
|开源|Qwen1.5-32B-Chat(new)|86|9|
|商用|minimax-abab6-chat(new)|86|10|
|商用|月之暗面kimichat|85|11|
|商用|商汤senseChat|85|12|
|开源|tigerbot-70b-chat-v3|85|13|
|开源|Qwen1.5-72B-Chat|84|14|
|开源|openbuddy-llama2-70b-v10.1|84|15|
|开源|XVERSE-65B-Chat|84|16|
|开源|tigerbot-70b-chat-v2|84|17|
|开源|AquilaChat2-70B-Expr|84|18|
|开源|openbuddy-llama-65b-v8|84|19|
|商用|微软new-bing|83|20|
|商用|baichuan3|83|21|
|开源|Baichuan2-13B-Chat|83|22|
|开源|openbuddy-zephyr-7b|83|23|
|开源|BlueLM-7B-Chat|83|24|
|商用|gpt-3.5-turbo|83|25|
|开源|tigerbot-13b-chat-v4|82|26|
|商用|阿里qwen-max|82|27|
|开源|Yi-34B-Chat|82|28|
|商用|讯飞星火v3|82|29|
|开源|aquilachat2-34b|82|30|
|商用|讯飞星火v1.5|81|31|
|开源|deepseek-llm-67b-chat|81|32|
|商用|阿里通义千问|81|33|
|开源|internlm2-chat-7b|81|34|
|开源|Qwen-72B-Chat|80|35|
|开源|internlm2-chat-20b|80|36|
|商用|minimax-abab5.5-chat(new)|79|37|
|开源|Qwen1.5-14B-Chat|79|38|
|开源|谷歌gemma-7b-it|79|39|
|商用|字节跳动豆包|77|40|
|开源|MiniCPM-2B-dpo|77|41|
|开源|Qwen1.5-7B-Chat|76|42|
|开源|Baichuan2-7B-Chat|76|43|
|商用|chatglm-turbo|75|44|
|商用|讯飞星火v2.0|75|45|
|开源|BELLE-Llama2-13B-chat-0.4M|74|46|
|开源|openbuddy-mixtral-7bx8-v17.1|73|47|
|开源|Qwen-7B-Chat|72|48|
|开源|xverse-13b-chat|72|49|
|开源|qwen-14b-chat|72|50|
|开源|miniCPM-2B-sft|72|51|
|开源|openbuddy-mistral-7b-v13.1|72|52|
|开源|Yi-6B-Chat|71|53|
|商用|360智脑|71|54|
|商用|chatglm-std|71|55|
|商用|chatglm-pro|70|56|
|开源|Baichuan-13B-Chat-v2|69|57|
|开源|chatglm3-6b|68|58|
|开源|Linly-Chinese-LLaMA2-13B|67|59|
|开源|Qwen-1_8B-Chat|66|60|
|开源|Llama-2-70b-chat|66|61|
|开源|Qwen1.5-4B-Chat|65|62|
|开源|openbuddy-openllama-3b-v10|60|63|
|开源|谷歌gemma-2b-it|60|64|
|开源|Qwen1.5-1.8B-Chat|58|65|
|商用|minimax-abab5.5s-chat(new)|57|66|
|开源|ziya2-13b-chat|54|67|
|开源|Qwen1.5-0.5B-Chat|40|68|

<br>

### 4、阅读理解能力排行榜
阅读理解能力是一种符合能力，考查针对给定信息的理解能力。
依据给定信息的种类，可以细分为：文章问答、表格问答、对话问答……
![lin](pic/mrc.png)

| 类别 | 大模型                         | 阅读理解能力 | 排名 |
|-----|------------------------------|---------|----|
|商用|gpt4|99.3|1|
|商用|GLM4|97.3|2|
|商用|minimax-abab6-chat(new)|96.7|3|
|商用|阿里qwen-max|95.3|4|
|商用|文心4.0|94.7|5|
|商用|微软new-bing|94.0|6|
|商用|gpt-4-turbo|94.0|7|
|商用|gpt-3.5-turbo|92.7|8|
|开源|Qwen1.5-32B-Chat(new)|92.7|9|
|开源|Qwen-72B-Chat|92.7|10|
|开源|AquilaChat2-70B-Expr|92.0|11|
|开源|Qwen1.5-14B-Chat|90.7|12|
|商用|baichuan3|90.7|13|
|商用|chatglm-turbo|90.0|14|
|商用|讯飞星火v3.5|89.3|15|
|商用|文心一言v2.2|88.0|16|
|开源|Qwen1.5-72B-Chat|88.0|17|
|商用|讯飞星火v3|88.0|18|
|开源|aquilachat2-34b|88.0|19|
|开源|openbuddy-llama2-70b-v10.1|86.7|20|
|开源|deepseek-llm-67b-chat|86.7|21|
|商用|minimax-abab5.5-chat(new)|86.7|22|
|开源|openbuddy-mixtral-7bx8-v17.1|86.0|23|
|开源|internlm2-chat-20b|86.0|24|
|商用|谷歌bard|85.3|25|
|开源|openbuddy-deepseek-67b|84.7|26|
|开源|qwen-14b-chat|84.7|27|
|开源|Yi-34B-Chat|84.7|28|
|商用|月之暗面kimichat|84.0|29|
|开源|tigerbot-70b-chat-v3|84.0|30|
|开源|XVERSE-65B-Chat|84.0|31|
|开源|Baichuan2-7B-Chat|83.3|32|
|商用|商汤senseChat|82.7|33|
|开源|xverse-13b-chat|81.3|34|
|商用|阿里通义千问|81.0|35|
|开源|tigerbot-13b-chat-v4|80.0|36|
|开源|tigerbot-70b-chat-v2|80.0|37|
|商用|字节跳动豆包|80.0|38|
|开源|Qwen1.5-4B-Chat|79.3|39|
|开源|openbuddy-llama-65b-v8|79.3|40|
|商用|讯飞星火v2.0|79.3|41|
|开源|chatglm3-6b|78.7|42|
|开源|miniCPM-2B-sft|77.3|43|
|开源|BELLE-Llama2-13B-chat-0.4M|76.0|44|
|商用|chatglm-std|76.0|45|
|开源|Qwen1.5-7B-Chat|76.0|46|
|商用|chatglm-pro|76.0|47|
|商用|讯飞星火v1.5|76.0|48|
|开源|Qwen-1_8B-Chat|75.3|49|
|开源|Baichuan2-13B-Chat|74.7|50|
|开源|Qwen-7B-Chat|74.0|51|
|商用|360智脑|74.0|52|
|开源|谷歌gemma-7b-it|74.0|53|
|开源|BlueLM-7B-Chat|74.0|54|
|开源|openbuddy-zephyr-7b|74.0|55|
|开源|MiniCPM-2B-dpo|74.0|56|
|开源|openbuddy-mistral-7b-v13.1|73.3|57|
|开源|Llama-2-70b-chat|73.3|58|
|开源|Baichuan-13B-Chat-v2|72.7|59|
|开源|internlm2-chat-7b|72.7|60|
|开源|ziya2-13b-chat|71.3|61|
|商用|minimax-abab5.5s-chat(new)|70.7|62|
|开源|Linly-Chinese-LLaMA2-13B|67.3|63|
|开源|Yi-6B-Chat|66.0|64|
|开源|openbuddy-openllama-3b-v10|61.3|65|
|开源|Qwen1.5-0.5B-Chat|60.0|66|
|开源|谷歌gemma-2b-it|60.0|67|
|开源|Qwen1.5-1.8B-Chat|52.7|68|

<br>

### 5、数据分析排行榜
暂不计入综合能力评分。
专门考查大模型对表格的理解分析能力，常用于数据分析。
![lin](pic/tableQA.png)

| 类别 | 大模型                         | 数据分析能力 | 排名 |
|-----|------------------------------|---------|----|
|商用|微软new-bing|100.0|1|
|商用|gpt4|97.0|2|
|商用|GLM4|96.0|3|
|商用|gpt-4-turbo|96.0|4|
|商用|文心4.0|94.0|5|
|开源|deepseek-llm-67b-chat|92.0|6|
|商用|gpt-3.5-turbo|91.3|7|
|商用|minimax-abab6-chat(new)|91.3|8|
|商用|阿里qwen-max|91.3|9|
|开源|Qwen1.5-14B-Chat|90.7|10|
|商用|月之暗面kimichat|89.3|11|
|开源|AquilaChat2-70B-Expr|89.3|12|
|开源|XVERSE-65B-Chat|89.0|13|
|开源|internlm2-chat-20b|88.0|14|
|开源|Qwen-72B-Chat|87.3|15|
|商用|讯飞星火v3.5|87.3|16|
|开源|Qwen1.5-72B-Chat|87.3|17|
|开源|Qwen1.5-32B-Chat(new)|87.3|18|
|商用|讯飞星火v3|86.0|19|
|开源|openbuddy-deepseek-67b|85.0|20|
|开源|tigerbot-70b-chat-v2|85.0|21|
|开源|tigerbot-13b-chat-v4|85.0|22|
|商用|baichuan3|84.7|23|
|开源|aquilachat2-34b|83.0|24|
|开源|internlm2-chat-7b|82.7|25|
|开源|openbuddy-mixtral-7bx8-v17.1|82.0|26|
|商用|字节跳动豆包|82.0|27|
|商用|chatglm-turbo|81.0|28|
|商用|文心一言v2.2|81.0|29|
|开源|BELLE-Llama2-13B-chat-0.4M|79.0|30|
|商用|商汤senseChat|78.0|31|
|开源|Baichuan2-13B-Chat|77.0|32|
|开源|Yi-34B-Chat|77.0|33|
|开源|qwen-14b-chat|77.0|34|
|商用|谷歌bard|77.0|35|
|开源|openbuddy-llama2-70b-v10.1|76.0|36|
|开源|openbuddy-llama-65b-v8|76.0|37|
|开源|openbuddy-mistral-7b-v13.1|76.0|38|
|开源|谷歌gemma-7b-it|76.0|39|
|商用|chatglm-pro|73.0|40|
|商用|阿里通义千问|73.0|41|
|商用|chatglm-std|73.0|42|
|商用|minimax-abab5.5-chat(new)|72.7|43|
|开源|BlueLM-7B-Chat|72.0|44|
|开源|openbuddy-zephyr-7b|72.0|45|
|开源|tigerbot-70b-chat-v3|71.0|46|
|开源|Qwen1.5-7B-Chat|70.7|47|
|开源|Llama-2-70b-chat|69.0|48|
|商用|讯飞星火v1.5|69.0|49|
|开源|Baichuan2-7B-Chat|69.0|50|
|开源|ziya2-13b-chat|68.0|51|
|开源|Baichuan-13B-Chat-v2|67.0|52|
|开源|xverse-13b-chat|67.0|53|
|商用|360智脑|66.0|54|
|开源|MiniCPM-2B-dpo|66.0|55|
|商用|讯飞星火v2.0|65.0|56|
|开源|Yi-6B-Chat|64.7|57|
|开源|Qwen1.5-4B-Chat|63.0|58|
|开源|chatglm3-6b|60.0|59|
|开源|Qwen-7B-Chat|59.0|60|
|开源|Linly-Chinese-LLaMA2-13B|57.0|61|
|商用|minimax-abab5.5s-chat(new)|56.0|62|
|开源|miniCPM-2B-sft|53.3|63|
|开源|Qwen-1_8B-Chat|51.3|64|
|开源|Qwen1.5-1.8B-Chat|48.0|65|
|开源|谷歌gemma-2b-it|43.3|66|
|开源|openbuddy-openllama-3b-v10|40.7|67|
|开源|Qwen1.5-0.5B-Chat|34.7|68|

<br>

### 6、中文编码效率排行榜
暂不计入综合能力评分。
专门考查大模型编码中文字符的效率，同等尺寸大模型，编码效率越高推理速度越快，几乎成正比。
中文编码效率相当于大模型生成的每个token解码后对应的中文平均字数
（大模型每次生成一个token，然后解码成真正可见的字符，比如中文、英文、标点符号等）。
![lin](pic/zhcoding.png)
<br>

## 🌐各项能力评分
评分方法：从各个维度给大模型打分，每个维度都对应一个评测数据集，包含若干道题。
每道题依据大模型回复质量给1~5分，将评测集内所有题的得分累加并归一化为100分制，即作为最终得分。

| 类别 | 大模型                          | 分类能力 | 信息抽取能力 | 阅读理解能力 | 数据分析能力 | 综合能力 |
|----|------------------------------|------|--------|--------|--------|------|
|商用|gpt4|94|94|99.3|97.0|96.1|1|
|商用|微软new-bing|95|83|94.0|100.0|93.0|2|
|商用|gpt-4-turbo|91|90|94.0|96.0|92.8|3|
|商用|GLM4|86|90|97.3|96.0|92.3|4|
|商用|文心4.0|88|89|94.7|94.0|91.4|5|
|商用|minimax-abab6-chat(new)|87|86|96.7|91.3|90.3|6|
|开源|Qwen1.5-32B-Chat(new)|91|86|92.7|87.3|89.3|7|
|商用|讯飞星火v3.5|87|92|89.3|87.3|88.9|8|
|商用|阿里qwen-max|86|82|95.3|91.3|88.7|9|
|商用|月之暗面kimichat|92|85|84.0|89.3|87.6|10|
|开源|Qwen1.5-14B-Chat|89|79|90.7|90.7|87.3|11|
|开源|Qwen-72B-Chat|89|80|92.7|87.3|87.3|12|
|开源|Qwen1.5-72B-Chat|89|84|88.0|87.3|87.1|13|
|商用|gpt-3.5-turbo|81|83|92.7|91.3|87.0|14|
|开源|internlm2-chat-20b|93|80|86.0|88.0|86.8|15|
|开源|AquilaChat2-70B-Expr|82|84|92.0|89.3|86.8|16|
|开源|deepseek-llm-67b-chat|87|81|86.7|92.0|86.7|17|
|商用|文心一言v2.2|90|87|88.0|81.0|86.5|18|
|开源|tigerbot-70b-chat-v2|97|84|80.0|85.0|86.5|19|
|开源|openbuddy-deepseek-67b|86|89|84.7|85.0|86.2|20|
|商用|baichuan3|86|83|90.7|84.7|86.1|21|
|商用|讯飞星火v3|87|82|88.0|86.0|85.8|22|
|开源|XVERSE-65B-Chat|83|84|84.0|89.0|85.0|23|
|商用|谷歌bard|86|88|85.3|77.0|84.1|24|
|开源|tigerbot-70b-chat-v3|94|85|84.0|71.0|83.5|25|
|开源|openbuddy-llama2-70b-v10.1|86|84|86.7|76.0|83.2|26|
|商用|chatglm-turbo|86|75|90.0|81.0|83.0|27|
|开源|tigerbot-13b-chat-v4|85|82|80.0|85.0|83.0|28|
|开源|Yi-34B-Chat|88|82|84.7|77.0|82.9|29|
|开源|aquilachat2-34b|77|82|88.0|83.0|82.5|30|
|商用|商汤senseChat|82|85|82.7|78.0|81.9|31|
|开源|openbuddy-mixtral-7bx8-v17.1|86|73|86.0|82.0|81.8|32|
|开源|internlm2-chat-7b|86|81|72.7|82.7|80.6|33|
|商用|minimax-abab5.5-chat(new)|83|79|86.7|72.7|80.3|34|
|开源|BELLE-Llama2-13B-chat-0.4M|90|74|76.0|79.0|79.8|35|
|商用|字节跳动豆包|79|77|80.0|82.0|79.5|36|
|开源|Baichuan2-13B-Chat|83|83|74.7|77.0|79.4|37|
|开源|qwen-14b-chat|84|72|84.7|77.0|79.4|38|
|开源|Baichuan2-7B-Chat|88|76|83.3|69.0|79.1|39|
|商用|阿里通义千问|81|81|81.0|73.0|79.0|40|
|开源|openbuddy-zephyr-7b|82|83|74.0|72.0|77.8|41|
|开源|BlueLM-7B-Chat|82|83|74.0|72.0|77.8|42|
|开源|openbuddy-llama-65b-v8|68|84|79.3|76.0|76.8|43|
|开源|xverse-13b-chat|86|72|81.3|67.0|76.6|44|
|商用|chatglm-std|84|71|76.0|73.0|76.0|45|
|商用|chatglm-pro|84|70|76.0|73.0|75.8|46|
|开源|Qwen1.5-7B-Chat|80|76|76.0|70.7|75.7|47|
|商用|讯飞星火v1.5|76|81|76.0|69.0|75.5|48|
|开源|谷歌gemma-7b-it|72|79|74.0|76.0|75.3|49|
|开源|openbuddy-mistral-7b-v13.1|79|72|73.3|76.0|75.1|50|
|商用|360智脑|86|71|74.0|66.0|74.3|51|
|开源|MiniCPM-2B-dpo|79|77|74.0|66.0|74.0|52|
|开源|Llama-2-70b-chat|86|66|73.3|69.0|73.6|53|
|开源|Qwen-7B-Chat|89|72|74.0|59.0|73.5|54|
|商用|讯飞星火v2.0|72|75|79.3|65.0|72.8|55|
|开源|Baichuan-13B-Chat-v2|82|69|72.7|67.0|72.7|56|
|开源|chatglm3-6b|82|68|78.7|60.0|72.2|57|
|开源|Qwen1.5-4B-Chat|75|65|79.3|63.0|70.6|58|
|开源|miniCPM-2B-sft|72|72|77.3|53.3|68.7|59|
|开源|Yi-6B-Chat|73|71|66.0|64.7|68.7|60|
|开源|ziya2-13b-chat|76|54|71.3|68.0|67.3|61|
|开源|Linly-Chinese-LLaMA2-13B|78|67|67.3|57.0|67.3|62|
|开源|Qwen-1_8B-Chat|73|66|75.3|51.3|66.4|63|
|商用|minimax-abab5.5s-chat(new)|58|57|70.7|56.0|60.4|64|
|开源|openbuddy-openllama-3b-v10|64|60|61.3|40.7|56.5|65|
|开源|谷歌gemma-2b-it|56|60|60.0|43.3|54.8|66|
|开源|Qwen1.5-1.8B-Chat|57|58|52.7|48.0|53.9|67|
|开源|Qwen1.5-0.5B-Chat|44|40|60.0|34.7|44.7|68|

<br>

## ⚖️原始评测数据
包含各维度评测集以及大模型输出结果，详见本项目的[eval文件目录](eval)
### 评测样本示例
| # | 分类评测样本                                                                        | 信息抽取评测样本                                                                                                                                                                             | 阅读理解评测样本                                                                                                                                                                                                                                                          |
|---|-------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1 | <div style="width: 250px">请分类以下5种水果：香蕉、西瓜、苹果、草莓、葡萄。</div>  | <div style="width: 250px">HR: 你好，我是XYZ公司的招聘主管。我很高兴地通知你，你已经通过了我们的初步筛选，并且我们希望邀请你来参加面试。<br>候选人：非常感谢，我很高兴收到你们的邀请。请问面试的时间和地点是什么时候和哪里呢？<br>HR: 面试的时间是下周二上午10点，地点是我们公司位于市中心的办公室。你会在面试前收到一封详细的面试通知邮件，里面会包含面试官的名字、面试时间和地址等信息。<br>候选人：好的，我会准时出席面试的。请问需要我做哪些准备工作呢？<br>HR: 在面试前，请确保你已经仔细研究了我们公司的业务和文化，并准备好了相关的问题和回答。另外，请务必提前到达面试现场，以便有足够的时间了解我们的公司和环境。<br>候选人：明白了，我会尽最大努力准备好的。非常感谢你的邀请，期待能有机会加入贵公司。<br>HR: 很高兴能和你通话，我们也期待着能和你见面。祝你好运，并期待下周能见到你。<br>基于以上对话，抽取出其中的时间、地点和事件。</div>&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; | <div style="width: 250px">牙医：好的，让我们看看你的牙齿。从你的描述和我们的检查结果来看，你可能有一些牙齦疾病，导致牙齿的神经受到刺激，引起了敏感。此外，这些黑色斑点可能是蛀牙。<br>病人：哦，真的吗？那我该怎么办？<br>牙医：别担心，我们可以为你制定一个治疗计划。我们需要首先治疗牙龈疾病，然后清除蛀牙并填充牙洞。在此过程中，我们将确保您感到舒适，并使用先进的技术和材料来实现最佳效果。<br>病人：好的，谢谢您，医生。那么我什么时候可以开始治疗？<br>牙医：让我们为您安排一个约会。您的治疗将在两天后开始。在此期间，请继续刷牙，使用牙线，并避免吃过于甜腻和酸性的食物和饮料。<br>病人：好的，我会的。再次感谢您，医生。<br>牙医：不用谢，我们会尽最大的努力帮助您恢复健康的牙齿。<br>基于以上对话回答：病人在检查中发现的牙齿问题有哪些？</div> |
| 2 | <div style="width: 250px">将下列单词按词性分类。<br>狗，追，跑，大人，高兴，树  </div>| <div style="width: 250px">给定以下文本段落，提取其中的关键信息。<br>今天早上，纽约市长在新闻发布会上宣布了新的计划，旨在减少治安问题。<br>该计划包括增加派遣警察的人数，以及启动社区倡议，以提高居民对警察工作的支持度。 </div> | <div style="width: 250px">文化艺术报讯 国务院办公厅发布关于2023年部分节假日安排的通知，具体内容如下：<br>元旦：2022年12月31日至2023年1月2日放假调休，共3天。<br>春节：1月21日至27日放假调休，共7天。1月28日（星期六）、1月29日（星期日）上班。<br>清明节：4月5日放假，共1天。<br>劳动节：4月29日至5月3日放假调休，共5天。4月23日（星期日）、5月6日（星期六）上班。<br>端午节：6月22日至24日放假调休，共3天。6月25日（星期日）上班。<br>中秋节、国庆节：9月29日至10月6日放假调休，共8天。10月7日（星期六）、10月8日（星期日）上班。<br>基于以上信息回答：2023年五一假期怎么放假。 </div>|
| 3 | <div style="width: 250px">将下列五个词分为两个组别，每个组别都有一个共同点：狗、猫、鸟、鱼、蛇。</div>&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp;&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp;| <div style="width: 250px">在给定的短文中找出三个关键词。<br>西方的哲学历史可上溯至古希腊时期，最重要的哲学流派包括柏拉图学派、亚里士多德学派和斯多葛学派。</div>| <div style="width: 250px">基于以下表格，请问张三的考勤情况<br>员工姓名,日期,上班时间,下班时间,是否迟到,是否早退,是否请假<br>张三,1月1日,8:30,17:30,否,否,否<br>李四,1月1日,9:00,18:00,是,否,否<br>王五,1月1日,8:00,16:30,否,是,否<br>赵六,1月1日,8:30,17:00,否,否,是<br>张三,1月2日,8:00,17:00,否,否,否<br>李四,1月2日,8:30,17:30,否,否,否<br>王五,1月2日,9:00,18:00,是,否,否<br>赵六,1月2日,8:30,17:00,否,否,是</div> |
| 4 | <div style="width: 250px">给定一组文本，将文本分成正面和负面情感。<br>举例文本:<br>这部电影非常出色，值得推荐。我觉得导演做得很好。<br>这场音乐会真是个灾难，我非常失望。</div>| <div style="width: 250px">从以下诗句中提取人物名称：两个黄鹂鸣翠柳，一行白鹭上青天。</div> | <div style="width: 250px">对于给定的问答对，判断问题是否被正确回答<br>问题：地球是第几颗行星？<br>答案：地球是第三颗行星。 </div>  |
| 5 | <div style="width: 250px">将以下10个单词分类为动物或植物。<br>树木、狮子、玫瑰、草地、松鼠、猴子、蘑菇、兔子、山羊、香蕉 | 明天天气怎么样？<br>广州明天最冷多少度？<br>广东大后天最暖多少度？<br>北京冷不冷？<br>提取出上述句子中的地理位置实体</div>  | <div style="width: 250px">根据以下文本回答问题：什么是能量守恒定律？<br>物理学是自然科学的一个重要分支，研究自然界的物质、能量、空间和时间等基本概念。<br>在物理学的研究中，科学家们探索了宇宙的奥秘，从微观粒子到宏观天体的各个方面都进行了深入研究。<br>在物理学中，一个重要的概念是能量守恒定律。能量守恒定律指出，一个孤立系统的总能量在任何时间都是不变的。<br>也就是说，能量不能被创造或摧毁，只能被转化成其他形式。<br>例如，当一个物体被提起并释放时，它的势能被转化为动能，使得物体开始运动。 </div>  |
|……|……|……|……|

### 大模型输出结果示例
|prompt|  <div style="width: 250px">chatgpt3.5</div>  | <div style="width: 250px">百度</div> | …… |
|-|-------------|------------------------------------------|----|
|<div style="width: 250px">将下列单词按词性分类。<br>狗，追，跑，大人，高兴，树</div>| <div style="width: 250px">好的，以下是这些单词按照词性分类后的结果：<br>名词：狗、大人、树<br>动词：追、跑<br>形容词：高兴 </div>| <div style="width: 250px">动物类别：狗<br>动作类别：追<br>动作类别：跑<br>情感类别：高兴<br>植物类别：树</div>&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; | …… |
|<div style="width: 250px">从以下诗句中提取人物名称：两个黄鹂鸣翠柳，一行白鹭上青天。</div>| <div style="width: 250px">这句诗出自唐代诗人杜甫的《绝句》，并没有明确提到人物名称。这句诗主要是在描绘自然景色，通过形象生动的语言来表现春天的美丽景象。<br>诗中提到“两个黄鹂”，“一行白鹭”，他们是动物而非人物名称。黄鹂是一种鸟类，它们身体鲜黄色，嘴巴呈钩形，叫声清脆悦耳；白鹭是另一种水鸟，身体白色，嘴巴细长，善于捕捉鱼类等。<br>杨婉这句诗意境深远，很好地表现了大自然的美丽和神奇。</div>| <div style="width: 250px">人物名称：黄鹂、白鹭 </div> | …… |
|……|……| …… |……|


## 为什么做榜单？
- 大模型百花齐放，也参差不齐。不少媒体的宣传往往夸大其词，避重就轻，容易混淆视听；而某些公司为了PR，也过分标榜自己大模型的能力，动不动就“达到chatgpt水平”，动不动就“国内第一”。
所谓“外行看热闹，内行看门道”，业界急需一股气流，摒弃浮躁，静下心来打磨前沿技术，真真正正用技术实力说话。这就少不了一个公开、公正、公平的大模型评测系统，把各类大模型的优点、不足一一展示出来。
如此，大家既能把握当下的发展水平、与国外顶尖技术的差距，也能更加清晰地看明白未来的努力方向，而不被资本热潮、舆论热潮所裹挟。
- 对于产业界来说，特别是对于不具备大模型研发能力的公司，熟悉大模型的技术边界、高效有针对性地做大模型技术选型，在现如今显得尤为重要。
而一个公开、公正、公平的大模型评测系统，恰好能够提供应有的助力，避免重复造轮子，避免因技术栈不同而导致不必要的争论，避免“鸡同鸭讲”。
- 对于大模型研发人员，包括对大模型技术感兴趣的人、学术界看中实践的人，各类大模型的效果对比，反应出了背后不同技术路线、技术方法的有效性，这就提供了非常好的参考意义。
不同大模型的相互参考、借鉴，帮忙大家躲过不必要的坑、避免重复实验带来的资源浪费，有助于整个大模型生态圈的良性高效发展。


