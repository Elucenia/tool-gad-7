<!-- ELUCENIA technical documentation · gad-7 · zh · no clinical/professional/rights approval -->

# GAD-7 量表

[条件、来源与许可](https://elucenia.org/zh/tools/gad-7)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 过去 2 周，以下问题多常困扰您？ 1. 感到紧张、焦虑或极度紧绷

`q1`

- `0` — 从未
- `1` — 几天
- `2` — 超过一半的天数
- `3` — 几乎每天

### 2. 无法停止或控制担忧

`q2`

- `0` — 从未
- `1` — 几天
- `2` — 超过一半的天数
- `3` — 几乎每天

### 3. 对各种事情过度担忧

`q3`

- `0` — 从未
- `1` — 几天
- `2` — 超过一半的天数
- `3` — 几乎每天

### 4. 难以放松

`q4`

- `0` — 从未
- `1` — 几天
- `2` — 超过一半的天数
- `3` — 几乎每天

### 5. 坐立不安到难以坐着

`q5`

- `0` — 从未
- `1` — 几天
- `2` — 超过一半的天数
- `3` — 几乎每天

### 6. 容易烦恼或易怒

`q6`

- `0` — 从未
- `1` — 几天
- `2` — 超过一半的天数
- `3` — 几乎每天

### 7. 害怕会发生可怕的事情

`q7`

- `0` — 从未
- `1` — 几天
- `2` — 超过一半的天数
- `3` — 几乎每天

## 方法版本

GAD-7/Spitzer 2006：7项0–3，总分0–21；5/10/15；巴西葡语Moreno 2016

## 已记录的公式

各项0（完全没有）至3（几乎每天）。总分0至21。严重度界值5、10、15。原始研究中广泛性焦虑筛查≥10的敏感度89%，特异度82%。

## 限制与适用人群

用于成人广泛性焦虑症状的筛查和强度测量。提示可能患病的结果需要进一步诊断评估。初级保健研究及巴西社区样本并不自动验证新的人群、本地实现或其他翻译。

## 参考文献

- [Spitzer RL et al. A brief measure for assessing generalized anxiety disorder: the GAD-7. Arch Intern Med, 2006.](https://doi.org/10.1001/archinte.166.10.1092)

- [Moreno AL et al. Factor structure, reliability, and item parameters of the Brazilian-Portuguese version of the GAD-7 questionnaire. Temas em Psicologia, 2016.](https://doi.org/10.9788/TP2016.1-25)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

轻度焦虑（0到4）

筛查工具：不能作出诊断。


### 2

中度焦虑（10到14）：筛查阳性

请用临床访谈确认：GAD、惊恐、社交焦虑和PTSD也会得高分。


### 3

重度焦虑（15到21）：筛查阳性

请用临床访谈确认并开始积极治疗。

