# Act绿色插件

为ACT和Trn添加一些绿色功能。基础代码复制自PostNamazu。具体使用方法请查看使用说明或导入触发器自行查看。

## 一般功能

### 更换鱼饵

**调用方法**: 
- 回调名称: `ChangeBait`
- 回调参数: `BaitId`

### 使用技能

相比原版的/ac，这个方法的优点是可以进入技能队列。

**一般技能**:

**调用方法**: 
- 回调名称: `SendAction`
- 回调参数: `ActionType`, `ActionId`, `TargetId`

**地面技能**:

**调用方法**: 
- 回调名称: `SendAction`
- 回调参数: `ActionType`, `ActionId`, `TargetId`, `<x|y|z>`

**使用物品**:

**调用方法**: 
- 回调名称: `SendAction`
- 回调参数: `ItemId`

## 绿色功能

### Tp

**Tp到坐标**:

**调用方法**: 
- 回调名称: `Tp`
- 回调参数: `x`, `y`, `z`

**Tp到鼠标坐标**:

**调用方法**: 
- 回调名称: `Tp`
- 回调参数: `mo`

### 天外飞仙

突进类技能无视距离，普通技能射程+2。

### 技能不位移

位移技能不产生位移。

### 防击退

字面意思。