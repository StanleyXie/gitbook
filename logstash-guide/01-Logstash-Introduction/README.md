# 第1章 简介

Logstash是一个实时流水线的开源数据采集引擎，它可以动态统一不同来源的数据，将数据规范化后输出到指定位置，为各种下游数据分析和可视化进行数据净化和通用处理。

虽然最初Logstash是用来驱动日志采集的一项创新，但其适用范围远超该场景。任何类型的事件都可以通过一种普适的流程进行丰富和转换——输入插件（Input plugins）、过滤插件（Filter plugins）和输出插件（Output plugins），并且有多种原生编解码器（Codec）可以对抽取过程进行进一步简化。Logstash运用大量的数据提升你的洞察力。
