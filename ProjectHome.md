# jQuery plugin for alert #

> 此插件旨在替代javascript原生的alert弹出窗口,使我们在表单校验时显示的提示信息对用户来说更友好.

> example:
> $('#tip).alert('hello world.');
> 这是一个最基本的使用方法,它将会在id为tip的元素左边显示一个DIV浮动层.

> example:
> $('#tip').alert({
> > position: 'right',
> > focus: true,
> > alertzIndex: 999,
> > alertClass: 'corner'

> });
> 我们可以通过插件提供的options参数,使DIV浮动层显示在我们想要的地方,或者是否在同时使其获得焦点,调整其显示的样式(样式定义请参照jquery.alert.css)