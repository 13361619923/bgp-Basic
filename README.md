# 关于BGP的ENSP实验项目

  主要实现的EBGP邻居的建立
  用两种不同的方式，实现网络互通
  解决路由黑洞3个方案

##       方案一 路由引入ospf

```
      R2 ospf 1 import-route bgp
      R4 ospf 1 import-route bgp
```


​      这样1.1.1.1可以ping通5.5.5.5


##       方案二 IBGP全互连




##       方案三（终极方案）MPLS多标签交换协议

