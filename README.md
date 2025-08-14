污污污污污www网站免费看在线

  input输入类型，当提交表单时，会对这些输入内容进行验证。而novalidate属性则用于在提交表单时不对form或input进行验证：

<form action="#" method="get" novalidate>
  E-mail:
  <input type="email" name="myEmail" />
  <input type="submit" />
</form>

 

新增的input属性

1.autofocus属性

   autofocus属性用于自动获取焦点。在html5中input元素设置该属性后，当页面加载时，input元素会自动获得光标焦点。

<input type="text" name="myTxt" autofocus />

2.form属性

  form属性用于设置input元素属于哪个表单。在html4中，表单中的所以元素都必须在这个表单的开始标签和结束标签之间，而在html5中，如果要将表单开始和结束标签之外的元素归属到该表单，只需要设置form属性
