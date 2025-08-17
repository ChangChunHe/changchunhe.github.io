---
title: "多元合金搜索(SAGAR程序)"
layout: single-portfolio
excerpt: "<img src='/images/research/sagar.jpg' alt=''>"
collection: research
order_number: 10
header: 
  og_image: "research/sagar.jpg"
---

# 用计算方法探索新材料：SAGAR 程序的实践

随着科技与工业的发展，人们对**新材料的探索**越来越重视。  
理论上，结合 **第一性原理计算** 和 **全局优化方法**，能够准确预测材料性质，从而加快新材料的发现过程。

---

## 挑战：多组分材料的复杂性

对于一些多组分体系，原子大多分布在接近晶格点的位置。  
在这种情况下，如果能够合理地设置偏向性筛选（biased screening），就能显著提升材料探索的效率：

- **避免重复结构**：利用空间群对称性，可以排除对称等价的重复候选。  
- **过滤不稳定候选**：通过能量约束条件，提前筛掉那些不可能稳定存在的结构。  

这样就能把计算资源集中在更有前景的候选材料上。

---

## SAGAR 程序：高效的结构生成与筛选

为了支持这一过程，研究者开发并发布了一个程序 —— **SAGAR (Structures of Alloy Generation And Recognition)**。  

特点：  
- 可以方便地通过网页使用；  
- 能自动结合对称性约束，快速生成可能的结构；  
- 通过预设条件筛选出合理候选，再交由第一性原理计算进行验证。  

---

## 应用示例

研究团队利用 SAGAR 展示了偏向性筛选的高效性和实用性：

1. **NaCl 中氯空位的分布**  
   - 模拟了高达 50% 的 Cl 空位浓度分布；  
   - 揭示了空位对材料性质的调控作用。  
![](https://raw.githubusercontent.com/ChangChunHe/changchunhe.github.io/refs/heads/master/images/research/sagar1.png)
2. **B/N 共掺杂金刚石**  
   - 预测了 **半导体-金属转变** 的可能性。  
![](https://raw.githubusercontent.com/ChangChunHe/changchunhe.github.io/refs/heads/master/images/research/sagar2.png)
3. **VCl₂ 的磁性结构**  
   - 确定了其基态的 **反铁磁排布**。  
![](https://raw.githubusercontent.com/ChangChunHe/changchunhe.github.io/refs/heads/master/images/research/sagar3.png)

4. **氢化 C₆₀ 结构**  
   - 找到了一些低能量且具备高对称性的候选结构。  
![](https://raw.githubusercontent.com/ChangChunHe/changchunhe.github.io/refs/heads/master/images/research/sagar4.png)

---

## 结论与意义

结果表明：  
通过引入 **偏向性筛选（biased screening）** 与 **合理约束条件**，材料探索的效率能够得到显著提升。  

这不仅帮助发现更稳定的候选结构，也为揭示新奇物性提供了有效工具。  
SAGAR 的推出，为计算材料学研究者提供了一条更高效的探索路径。

---

✨ 总的来说，SAGAR 就像一个“材料发现加速器”：  
它利用对称性和筛选规则，帮我们更快找到有趣又稳定的新材料。

