- 自动下载电路的三极管封装中 B E 引脚弄反了
- 充电状态检测电路中，在 esp32 断电后 io 并不是高阻状态导致充电指示灯一直亮着，应该加下拉电阻
- 插入 USB 后应用USB供电，而不是用电池，防止充电芯片一直输出电流，导致充电灯常亮。