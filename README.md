# Endurance 简体中文补丁

《星际穿越》永恒号部件包（[Endurance](https://spacedock.info/mod/1059)，作者 JPLRepo）的简体中文汉化。

用 ModuleManager 补丁实现，**只改文本，不动任何数值**。

## 覆盖范围

- 23 个零件的 `title` / `description`
- 零件右键菜单（PAW）里的动作文本：居住舱充气/收拢、支腿、旗帜、科学容器（查看/存储）、
  乘员报告、各类实验，以及燃料电池 / 托卡马克 / EPS 变压器等转换器的启动、停止、切换
- 实验定义 `habcheck`（宜居性评估）的标题与全部结果文本

全部用 `:FINAL` 保证在所有其它补丁之后生效。

## 依赖

- Endurance（本体）
- ModuleManager

## 安装

把 `GameData\Endurance_CN` 放进 KSP 的 `GameData` 目录。

## 卸载

删掉 `GameData\Endurance_CN` 整个目录即可，不残留任何改动（补丁不改模组原文件）。

## 说明

- 本补丁只包含汉化文本，**不包含 Endurance 本体的任何资源**，使用前请先安装本体。
- 原文以行内注释形式保留在 cfg 里，方便核对与回退。

## 授权

MIT

---

# Endurance CN

Simplified Chinese localization patch for the [Endurance](https://spacedock.info/mod/1059) parts pack
by JPLRepo, implemented as a ModuleManager patch. Text only - no values are changed.

Requires Endurance and ModuleManager. Drop `GameData\Endurance_CN` into your KSP `GameData`.
Licensed MIT. Contains no assets from the original mod.
