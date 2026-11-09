# RECCVS Goal C · 单解可见曲率奇点

**状态：开放。** 在单个实际解中寻找有限仿射长度的奇异端点，沿统一归一化的平行传播框架或通过曲率标量证明发散，再证明存在从该端点逃逸至同一已识别未来零无穷远的出射零线。

## 证明稿与验收

| 材料 | 范围 |
|---|---|
| [L004](proofs/RECCVS_L004.md)、[L005](proofs/RECCVS_L005.md) | 中心出射聚焦、电荷接口与坐标退化的诊断 |
| [L007–L012](proofs/INDEX.md) | 特殊形成输入下的实际内侧区域控制 |
| [L013–L016](proofs/INDEX.md) | 散射迹、中心体积与轴线寿命、局部曲率恒等式 |
| [L017–L019](proofs/INDEX.md) | 中心能量、谱判据、边际球刚性与仿射预算 |

分别记录轴线固有时、零线仿射长度、曲率发散、延拓正则性与可见性。条件性内部分类注明实际解、区域和前置尾部假设。有限轴线寿命本身只提供端点分析的起点。

## 研究入口

- [共享模型 D004](https://github.com/Yelena0178/Regular-Extremal-Critical-Collapse-and-Visible-Singularities/blob/fe457f6ea98818251f97251c4a1f7a50b862253b/definitions/MODEL.md)
- [形成输入与全中心链审计](https://github.com/Yelena0178/Regular-Extremal-Critical-Collapse-and-Visible-Singularities/blob/fe457f6ea98818251f97251c4a1f7a50b862253b/inputs/AUDIT.md)
- [任务 R06、R07](https://github.com/Yelena0178/Regular-Extremal-Critical-Collapse-and-Visible-Singularities/blob/fe457f6ea98818251f97251c4a1f7a50b862253b/ROADMAP.md)
- [任务 T09、T10](https://github.com/Yelena0178/Regular-Extremal-Critical-Collapse-and-Visible-Singularities/blob/fe457f6ea98818251f97251c4a1f7a50b862253b/proofs/ROUTES_AND_TASKS.md)
- [平行传播潮汐分量 L003](https://github.com/Yelena0178/RECCVS-B-Visible-Curvature/blob/20e39906b1a492f03660276c228fd5987b3db06e/proofs/RECCVS_L003.md)
- [Goal A 的有限时间陷俘判据 L001](https://github.com/Yelena0178/RECCVS-A-Extremal-Threshold/blob/59617870d6fe98db287dbe91ca6270f9e5460c88/proofs/RECCVS_L001.md)

## 核代数复算

```bash
python -m pip install -r experiments/requirements-kernel.txt
python experiments/kernel_algebra.py
python checks/verify_manifest.py
```

核代数脚本检查 L012 的显示恒等式。PDE 延续与因果边界需要独立论证。

## 来源与引用

- [RECCVS 总入口](https://github.com/Yelena0178/Regular-Extremal-Critical-Collapse-and-Visible-Singularities)
- [此专题所用的原仓快照](https://github.com/Yelena0178/Regular-Extremal-Critical-Collapse-and-Visible-Singularities/tree/fe457f6ea98818251f97251c4a1f7a50b862253b)
- [文件来源与校验](PROVENANCE.md) · [引用信息](CITATION.cff) · [许可状态](LICENSE_NOTICE.md)
