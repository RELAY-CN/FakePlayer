## FakePlayer
用于在 Rusted Warfare 的房间上通过 端口代理 等多种方式实现虚假的玩家  

默认方案
> 创建一直在的玩家  

可以实现
> 且会随机重复房间内的一句话 (5%概率) 
> 可以在开始后正常游戏 (高难度AI)  
> 完整模仿协议, 无法以正常手动查出  

我们致力于让游戏环境变得更好, 即使是被动行为.   
**不为此负责**  

## Tags
`红队` `攻击性`   

## 使用
### 单个玩家
```text
java -jar player.jar ip:port isudp [passwd]
```
例子
```text
java -jar player.jar 1.1.1.1:5123 false
```

## 其他
仅供压测

### Licenses  
[RELAY-CN 团队专用软件许可证](https://github.com/RELAY-CN/.github/blob/main/LICENSE.md)
