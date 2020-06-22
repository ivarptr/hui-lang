# MASM 和 DOS

传统汇编教材的调试环境：

1. DOSBox
   [https://www.dosbox.com/](https://www.dosbox.com/)
   在 Windows 7,10/Linux/macOS 里模拟 DOS

2. MASM 611
   [https://sourceforge.net/projects/masm611/](https://sourceforge.net/projects/masm611/)
   MASM 工具链

3. DEBUG
   可以在 FreeDOS（https://www.freedos.org/）的 ISO 光盘里提取

## DOSBox 配置

配置文件位于 `/.dosbox/dosbox-x.xx-x.conf`

```toml
[sdl]
windowresolution=1600x1200
output=opengl

[autoexec]
mount c ~/dosbox-c
set PATH=c:\masm611\bin;c:\debug
c:
```


