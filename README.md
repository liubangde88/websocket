wocket 连接测试交互工具

使用命令： -r 后面的参数只是一个参考格式，不能原样复制(默认是有以下请求头，原样输入会报错请求头重复)，一般ws请求时header中通常会根据业务情况会有一些特殊的请求头，请以示例格式输入

`ws -h ws://127.0.0.1:8000 -r '{"Upgrade":"websocket", "Accept-Language": "zh-CN,zh;q=0.9"}'
`
 