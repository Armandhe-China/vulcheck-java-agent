## 检测能力
![](./污点流转.png)

上面是一处较深的命令执行漏洞案例，污点由source点开始经过了各种字符串变换（传播节点）最终流入到
Runtime.getRuntime().exec()方法