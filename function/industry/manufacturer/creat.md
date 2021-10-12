# 新增厂商

## 入口

在列表中点击“新增”按钮，进入“新增厂商”的页面。

![新增厂商](<../../../.gitbook/assets/image (14).png>)

## 基础信息

| 数据   | 是否必填 | 规则                                                                      |
| ---- | ---- | ----------------------------------------------------------------------- |
| 厂商名称 | 必填   | <p>1~24个任意文字<br>不能与其他未删除的厂商重名</p><p>名称显示在场馆端App中</p>                    |
| 所在地  | 必填   | 选择1个厂商所在的省份和城市                                                          |
| logo | 必填   | <p>1张1M以内的jpg或png图片</p><p>logo也会展示在普通推荐位（如果有这个厂商的话）</p>                 |
| 简介   | -    | 1\~500个任意文字                                                             |
| 标签   | -    | <p>可输入1~12个任意文字的关键词搜索并选择1个或多个标签</p><p><strong>不会显示</strong>在场馆端App中</p> |
| 排序   | -    | <p>1~4位且>0的数字，不支持小数点</p><p>数值越小，在场馆端App中越优先显示（在器材资讯的厂商列表中）</p>          |
| 推广标记 | -    | <p>已认证：在场馆端App中的厂商名称后面显示“认证”图标。</p><p>置顶：在器材资讯的厂商列表中优先展示置顶厂商。</p>       |

{% hint style="info" %}
图片建议尺寸（或等比例尺寸）：

厂商logo：164px × 52px
{% endhint %}

{% hint style="info" %}
“标签”是在后续版本的个性推荐业务中作为核心信息之一使用，目前版本仅作数据收集。
{% endhint %}

## 联系信息

最多可以添加10组联系信息。

| 数据 | 是否必填 | 规则         |
| -- | ---- | ---------- |
| 名称 | 必填   | 1\~8个任意文字  |
| 电话 | 必填   | 6\~20个任意文字 |

{% hint style="info" %}
若不需要联系信息，“名称”和“电话”都留空即可。\
但若只填了“名称”或“电话”，那么另外一个也必须要填写。
{% endhint %}

{% hint style="info" %}
若不填写联系信息，在场馆端App的商品详情中不会展示“获取联系方式”的入口。
{% endhint %}