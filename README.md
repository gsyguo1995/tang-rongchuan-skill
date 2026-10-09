# 唐容川 Skill（tang-rongchuan）

**v1.0.0** · 清末中西医汇通学派创始人、《血证论》作者唐容川（唐宗海，约1846-1897）的人物 skill，AI 能以其视角进行血证辨治、气血水火病机分析与中西汇通讨论。

[![版本](https://img.shields.io/badge/版本-v1.0.0-blue)](CHANGELOG.md)
[![原文库](https://img.shields.io/badge/原文库-5部29.7万字可grep-orange)](modules/)
[![License](https://img.shields.io/badge/协议-MIT-green)](LICENSE)

> 「水即化氣，火即化血。」—— 唐容川《血证论·阴阳水火气血论》

> ⚠️ 仅供学习研究，不构成医疗建议。血证属急症，任何出血请立即就医。

---

## 一句话介绍

因父患血证遍治无效，愤而弃儒习医，十一年著成中国第一部血证专书《血证论》，创**止血、消瘀、宁血、补虚**四大法；后又开"中西汇通"先河——张锡纯读其书"靈明頓開"，直接催生《医学衷中参西录》。

**直接激活词**：`唐容川` / `容川视角` / `血证思维` / `汇通派`

## 功能矩阵

| 能力 | 说明 |
|:---|:---|
| 血证四大法 | 止血→消瘀→宁血→补虚，次第铁律，22 个急救场景方药 |
| 气血水火棱镜 | 任何症状过四问（气病/血病/水病/火病）+ 互及律 |
| 方药体系 | 泻心汤加味法/大黄止血论/十灰散/独参汤，原文剂量 |
| 汇通论证 | "以西证中"工具主义 + 三焦发明（腎系連網即三焦） |
| 七步辨治法 | 定性→审来路→棱镜→虚实比例→四法阶段→归经→方药 |
| FAQ 直答 | 10 题高频（含医史：与张锡纯关系/汇通立场） |
| 原文检索 | 5 部著作全文入库，回答可 grep 引用 |

## 快速安装

```bash
git clone https://github.com/gsyguo1995/tang-rongchuan-skill.git ~/.claude/skills/tang-rongchuan
```

## 数据来源

| 著作 | 卷数 | 内容 |
|---|---|---|
| 血证论 | 8卷 | 代表作（1884），第一部血证专书 |
| 中西汇通医经精义 | 2卷 | 汇通标志（1892） |
| 医学见能 | 4卷 | 入门诊籍 |
| 本草问答 | 3卷 | 问答体药理 |
| 医易通说 | 2卷 | 医易同源 |

底本：中医笈成 jicheng.tw 开放数据库，公有领域。
学术来源：[江苏省中医药博物馆](https://museum.njucm.edu.cn/2024/0321/c6273a124573/page.htm)、[四川省中医药管理局·川派名医志](https://sctcm.sc.gov.cn/sctcm/zyywh/2023/5/5/80ccaa1718ed49d39bbec42cf28e92e5.shtml)（均 HTTP 200 已验证）。

## 目录结构

```
tang-rongchuan/
├── SKILL.md              # 主技能文件（自包含）
├── modules/              # 5部原文全文（29.7万字）
│   ├── 00_index.md
│   ├── 01-xuezheng-lun.md      # 血证论
│   ├── 02-yijing-jingyi.md     # 医经精义
│   ├── 03-yixuejianneng.md     # 医学见能
│   ├── 04-bencao-wenda.md      # 本草问答
│   └── 05-yiyitongshuo.md      # 医易通说
├── references/
│   ├── 00-keyword-index.md     # 关键词索引
│   ├── 07-patterning-framework.md # 七步辨治法+气血水火棱镜
│   ├── 08-faq.md               # 10题直答
│   └── 09-clinical-safety.md   # 血证急救+铁律
├── knowledge/research/   # 蒸馏研究笔记
└── CHANGELOG.md
```

## 相关项目

| 项目 | 坐标系 | 说明 |
|:---|:---|:---|
| [陈士铎](https://github.com/gsyguo1995/chen-shiduo-skill) | 真假之辨+五行生克 | 同为本文作者蒸馏，清初辨证大师 |
| [倪海厦](https://github.com/jangviktor-web/nihaixia) | 经方·六经辨证 | tcm-distiller 同源 |
| [张锡纯]（待蒸馏） | 衷中参西 | 直接受唐容川启发 |

## 免责声明

本项目内容仅供中医学习与研究，为清末历史医学视角的思维模式重建，不构成医疗建议。血证属急重症，任何出血症状请立即就医。所有诊疗请务必咨询执业中医师。

---

*Generated with Distilly + tcm-distiller 方法论 · 2026-10-09*
