# canDragCodeEditor
可以拖拽的代码编辑器，既实现了代码编辑器，又实现了拖拽。主要功能在index.html中实现。

index.html一共有三个方法：
* instructEditor: 用于实例化编辑器； 使用的是ace库
* initDrag: 用于实现拖拽；使用的是jquery-ui库
* resetPosition: 用于将拖拽元素复位

三个方法互不影响，需要哪个功能直接使用对应的 方法即可；