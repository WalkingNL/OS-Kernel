## Linux深度学习

#### 掌握 /proc 文件
这里有一篇介绍/proc的[文章](http://mentorembedded.github.io/advancedlinuxprogramming/alp-folder/alp-ch07-proc-filesystem.pdf)，一下的内容很多都是来自其中。

`proc`是一种存在于正在运行着的Linux内核中的窗口，在`/proc`文件系统中的文件，没有对应的真实的文件，相反，只是一些行为类似普通文件，但却提供了访问入口，可以访问到内核中的参数，数据结构，及其它数据。这些文件的"内容"并不像普通文件那样，总是有固定的数据块。而是，当你从这些文件中读取内容的时候，由Linux内核在其上动态生成相应的内容。
> proc is a window into the running Linux kernel，

