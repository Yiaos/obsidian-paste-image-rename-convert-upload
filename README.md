# Stupid Image Process

使用Cursor和Claude打造

General by cursor & claude

抄袭自以下代码库

1. https://github.com/reorx/obsidian-paste-image-rename

2. https://github.com/musug/obsidian-paste-png-to-jpeg

使用方法见它们的README ：）


为什么写这个插件

我的需求：

1. 图片粘贴到note时，自动重命名https://github.com/reorx/obsidian-paste-image-rename完美满足需求
2. 图片能够压缩，以占用更少的空间https://github.com/musug/obsidian-paste-png-to-jpeg非常好的满足需求
3. 在重命名之后能自动上传到cloudflare R2 对象存储
   1. https://github.com/renmu123/obsidian-image-auto-upload-plugin + picgo 能够满足需求，但是我希望在不使用额外工具的情况下（如picgo)达成目标

So, 我借助Cursor + Claude 抄袭了以上插件仓库，合并成1个插件。

Bug一定有，因为我总共只用了半天时间， 并没有充分测试

代码可读性和可扩展性也有限，即使我再没加入一个功能都要求Claude按要求优化代码

It's just a STUPID Image Process
