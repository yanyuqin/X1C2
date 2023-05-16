# ThinkPad X1 Carbon BIOS mod

Hi! I'm your first Markdown file in **StackEdit**. If you want to learn about StackEdit, you can read me. If you want to play with Markdown, you can edit me. Once you have finished with me, you can create new files by opening the **file explorer** on the left corner of the navigation bar.


# Files

StackEdit stores your files in your browser, which means all your files are automatically saved locally and are accessible **offline!**

## BIOS 修正打补丁

     #UEFIPatch x1c2-ch341-1.bin xx40_xx50_patches_v7.txt -o x1c2-patch.bin 
     parseVolume: unknown file system FFF12B8D-7696-4C8B-A985-2747075B4F50  
     parseVolume: unknown file system 00504624-8A59-4EEB-BD0F-6B36E96128E0  
     parseFile: non-empty pad-file contents will be destroyed after volume modifications
     patch: replaced 5 bytes at offset 8DFh 41390B7517 -> 41390B7500
     patch: replaced 6 bytes at offset 8F5h 41394B04741B -> 41394B04EB1B
     patch: replaced 9 bytes at offset 858h 41390B0F8469010000 -> 41390B48E969010000
     patch: replaced 16 bytes at offset 3E0h 04320B483CC2E14ABB16A73FADDA475F -> 778B1D826D24964E8E103467D56AB1BA
     Image patched>


##  BIOS 清零
Disconnect all batteries for about 10 minutes. Afterward connect charger and hold power button for 30 seconds, this clears the EC, and should bring you into a full cold boot state.
断开所有电池约10分钟。然后连接充电器并按住电源按钮30秒，这将清除EC，并将使您进入完全冷启动状态。


[参考1](https://github.com/simprecicchiani/ThinkPad-T460s-macOS-OpenCore/blob/master/Guides/Bios-Mod.md)

[参考2 补丁源文件及方法](https://github.com/digmorepaka/thinkpad-firmware-patches)

[T440 mod BIOS](https://notthebe.ee/blog/removing-the-wifi-whitelist/)

[编程器软件AsProgrammer](https://github.com/nofeletru/UsbAsp-flash)
