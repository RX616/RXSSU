# RXSSU - 魔改版的KernelSU
# 深度魔改
通杀大量环境检测软件，挑战极限。
采用 KernelSU V2.1.2 版本进行魔改，使用挂载模块无需刷元模块，只需关闭默认卸载模块即可。
后续将对挂载类进行深度隐藏并增加内置 Zygisk 和全局 Ticky Store。
# LKM 模式
支持，可直接在管理器修补 init_boot 并刷入，但无法保证0模块过大量环境，隐藏效果不如 GKI 和 Vendor。
# GKI 模式
不支持，目前 GKI 编译脚本没做好，隐藏效果不如 Vendor。
# Vendor 模式
支持，可直接在管理器修补 vendor_boot 并刷入，隐藏效果更好，通杀大量环境检测软件，比 GKI 和 LKM 更好。
天玑设备可能无法使用。
