# 前端常见面试知识点

css篇

1，flex 弹性布局
2，animate transition transform translate;
3,


实践篇
1，工厂模式 es6工厂模式
function obj(){
  var o = new Object();
  o.name = 'test';
  o.say(){};
  return o;
}


class person{
  constructor(){
    this.name = 'test';
  }
  say() {
  
  }
}

2，lazyman

3，转换为tree树状结构

4，js 常见类型 clone

function clone(obj){
	var o;
 	if(typeof obj == 'object'){
		if(obj instanceof Array){
			o = obj.slice(0);
		}else{
			o = JSON.parse(JSON.stringify(obj));
        }
    }else{
		o = obj;
    }
	return o;
}


