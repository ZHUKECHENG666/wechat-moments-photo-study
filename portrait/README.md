[返回实验报告](../README.md)

# 人像实测结果

快速 CNN 发送稿为 **3.13 MB**，朋友圈实收 **0.47 MB**。预测与实收均为 **77.33 分**，解码后逐像素一致。

## 实测结果

<table>
<thead><tr><th>场景</th><th>方案</th><th>发尺寸</th><th>收尺寸</th><th>对比原图的色差 ↓</th><th>综合评分 ↑</th></tr></thead>
<tbody>
<tr><th rowspan="3">人像</th><td>原图直发</td><td>5651×3767<br>19.471 MB</td><td>2880×1920<br>0.438 MB</td><td>1.682</td><td>74.69</td></tr>
<tr><td>Photoshop</td><td>2880×1920<br>16.598 MB</td><td>2880×1920<br>0.461 MB</td><td>1.674</td><td>75.64</td></tr>
<tr><td>快速 CNN · 轻量 JPG</td><td>2880×1920<br>3.133 MB</td><td>2880×1920<br>0.470 MB</td><td>1.709</td><td><strong>77.33</strong></td></tr>
</tbody>
</table>

把参考图及实收图统一缩到长边 1080 像素后，原图直发为 90.03 分，Photoshop 为 90.41 分，快速 CNN 为 90.62 分。

[返回总表与指标说明](../README.md#实验结果)
