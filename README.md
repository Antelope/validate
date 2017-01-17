用法
var msg = Validate({
	name:xxx, //提交校验的姓名
	cardnum:xxx, //身份证号码
	phone:xxx,  //手机号码
	email:xxx,  //邮箱	
});

Validate 返回的是校验的错误信息，如果校验通过则返回 true;