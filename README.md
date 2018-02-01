该分页插件使用简单，体积小，使用方法如下：  

## 在页面上插入
&lt;nav aria-label="Page navigation"&gt;  
    &nbsp;&nbsp;&nbsp;&nbsp;&lt;ul class="pagination"&gt;  
    &nbsp;&nbsp;&nbsp;&nbsp;&lt;/ul&gt;  
&lt;/nav&gt;  

## 调用方法
$(".pagination").initPagination('formId',20,{  
			&nbsp;&nbsp;&nbsp;&nbsp;pageNum: 1,  
			&nbsp;&nbsp;&nbsp;&nbsp;pageSize: 10  
		});  
    
## 参数说明
initPagination(formId,pages,option)  
* formId：表单id
* pages：总页数
* pageNum：当前页数
* pageSize：每页数量

![](pic1.png)
