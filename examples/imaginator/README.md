Cybros Imaginator
====

一个基于 Stable Diffusion 的 Web 3 native 的包含确权信息的图片 NFT 生成器

## 使用方法

提交 Prompt，返回可用于铸造 NFT 的 metadata 的 Arweave URL。

## 特点

### 类 Midjourney 的交互

参考 prompt：

```
closeup portrait of nkoctst cat in a misty field, dream landscape, simulation, physical particles, translucence, cinematic lighting, iridescence, digital painting
--neg blurry, artifacts, duplicate, mutilated, mutation, deformed, ugly, blurry, bad anatomy, lowres, bad anatomy, text, error, cropped, worst quality, low quality, normal quality, jpeg, signature, username, blurry, artist name, longhair, clothes, too many ears, border,
--model nekothecat_nekov3
--sampler DPM adaptive
--steps 20
```

### 可确权

利用 SD 的特点，相同模型相同参数生成的图片相同，可以将生成相关的材料整理成“对发明图片”的证明。

### Web 3 native

消费端（最终用户）通过区块链提交 Prompt。
可以通过跨链消息传递来部署到各种区块链网络。
并且产生的 Metadata 也可以提交到任意 NFT 市场。
也可以利用 Web3 的“可组合性”来设计新的玩法

供给端（提供计算资源的节点）可以去中心化部署，利用区块链经济模型（如 staking）来获取收益，并且也可降低消费端的成本。
SD 并不需要非常高端的硬件，闲置的 3080 足以跑大多数模型和生成较高分辨率的图片了，理想情况，任何闲置的 GPU 都可以部署这套服务，使得成本大幅度降低。
硬件成本是目前商业产品面临的比较大的问题，也有一些降本的措施，但是显然区块链和共享经济可以进一步降低成本。
