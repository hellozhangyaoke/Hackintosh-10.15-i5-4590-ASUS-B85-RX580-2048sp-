# 黑苹果10.15.7(Intel 4th处理器/RX580 2048SP)

## 硬件说明
-   CPU -- i5 4590
-   内存 -- 金士顿 8G*2
-   主板 -- 华硕B85 Plus R2.0
-   显卡 -- 铭瑄RX580 2048SP 8G
    - 因为2048SP的RX580不支持原生驱动，这里我刷成了RX570，刷的微星BIOS

## 完美运行的硬件
-   显示正常，支持我2K 144hz的显示器
-   硬件解码支持，支持调用HD4600解码
-   声音正常，前后面板音频、麦克风接口均正常运作
-   鼠标、键盘等均正常
-   睡眠正常
## 你需要做的事
-   关闭VT-d
-   显卡如果是2048SP的RX580，需要先刷成RX570，如果你是其他amd显卡，可以google一下是否免驱。
-   关闭主板的安全启动和csm兼容
## 支持的系统
-   测试过10.14、10.15均正常运行
-   按道理只需要升级一下驱动就可支持big sur，不过我没测试过不敢保证。
