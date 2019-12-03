# pagination
使用jQuery开发的分页插件

### 使用方法
1. 导入相关的css、js文件
```html
<link rel="stylesheet" type="text/css" href="css/zxf_page.css"/>
<script src="js/jquery-3.2.1.min.js" type="text/javascript" charset="utf-8"></script>
<script src="js/zxf_page.js" type="text/javascript" charset="utf-8"></script>
```
2. 导入相关的css、js文件
```html
<div class="zxf_pagediv"></div>
```
3. 导入相关的css、js文件
```Javascript
<script type="text/javascript">
    $(".zxf_pagediv").createPage({
        pageNum: 50,//总页码
        current: 30,//当前页
        backfun: function(e) {
                //console.log(e);//回调
        }
    });
</script>
```
---

[插件最初发布地址及部分问答](https://www.jq22.com/jquery-info13703 "最初发布地址")

---

#### 更新情况

##### 更新发现的Bug

##### 更新时间：2017-5-3，更新内容
1. shownum://每页显示个数，最小值5
2. activepage当前页选中样式
3. activepaf下一页选中样式
4. 确认按钮对enter键的支持
