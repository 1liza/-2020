# HTML标签

## label

label只有两个属性for（规定 label 绑定到哪个表单元素）和form（规定 label 字段所属的一个或多个表单）

## input

 disabled指当 input 元素加载时禁用此元素。input内容不会随着表单提交
 readonly规定输入字段为只读。input内容会随着表单提交。
无论设置readonly还是disabled，通过js脚本都能更改input的value（亲测可以）

![img](img/input.png)

## a

_blank	在新窗口中打开被链接文档。
_self	默认。在相同的框架中打开被链接文档。
_parent	在父框架集中打开被链接文档。
_top	在整个窗口中打开被链接文档。
framename	在指定的框架中打开被链接文档。

## meta

<meta> 元素可提供有关页面的元信息（meta-information），比如针对搜索引擎和更新频度的描述和关键词。
<meta> 标签位于文档的头部，不包含任何内容。
<meta> 标签的属性定义了与文档相关联的名称/值对。

<mark> 标签定义带有记号的文本。请在需要突出显示文本时使用 <m> 标签。

## 自关闭标签

HTML5中：
自关闭的斜线(/)对 ：area, base, br, col, command, embed, hr, img, input, keygen, link, meta, param, source, track, wbr空标签无效，言即不再需要自闭合(/)这个小尾巴了，如果要写上也是可以的。