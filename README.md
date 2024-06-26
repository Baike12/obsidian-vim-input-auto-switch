# obsidian中数学公式块中不切换中文输入法
## 需求背景：使用obsidian的vim模式时，如果需要在normal模式和insert模式中切换中英文输入法，可以安装vim im select插件，但是这个插件会使得在输入公式时也切换到中文输入法，这个仓库中的代码解决了这个问题，使得在数学块中保持英文输入法。
## 使用方式：
1. 如果已经安装了vim im select，先卸载vim im select；
2. 将本仓库中的代码拷贝到你存放第三方插件的目录下；
3. 修改代码中im-select.exe的路径（修改方法见注意事项中的描述），如果还没安装im-select.exe，在github中搜索下载；
4. 重启obsidian即可生效；
## 注意事项：
- 由于我最近工作重点不在插件开发上，所以代码讲究一个能用就行，实现非常粗暴，代码中都是写死的，但是我自己用下来暂时没啥问题，后续不那么忙了会抽时间改进；
- 所以目前只支持1033（英文），2052（中文）输入法；
- 你需要在代码中搜索"im-select.exe 2052"（没有引号），然后把im-select.exe的路径改成你自己的；
- 这份代码是基于obsidian-latex-suite和obsidian-vim-im-select插件魔改的，**分别向obsidian-latex-suite作者artisticat1、obsidian-vim-im-select作者alonelur两位大佬致敬**，这份代码可以实现两个插件的功能，但是只保留了obsidian-latex-suite的配置页面，因为obsidian-vim-im-select的配置在代码中写死了:)
# 最后再次分别向obsidian-latex-suite作者artisticat1、obsidian-vim-im-select作者alonelur两位大佬致敬
如果可以的话给我点个star哦，~.~爱你
或者可以请我喝杯茶，谢谢啦

![image](https://github.com/Baike12/obsidian-vim-input-auto-switch/assets/134204678/74a2e14c-14ce-412a-bff7-80b249fb4de7)
