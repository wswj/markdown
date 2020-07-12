# .Net:持续进化的统一开发平台
> 阅读文本大概需要8分钟
标题使用的是**进化**两个字,是*因为*.net在不断努力
## 持续进化的.net

![a.jpg](a.jpg)
- 无序列表
- a
- b
- c
1. a
2. c
3. b
# 超链接
- 外链
- [百度](http://www.baidu.com)
- 内链
- [1](#持续进化的net)
# 复选框
- [ ] 任务1
- [X] 任务2
# 代码
- 短代码
` Student1 model = student; ` 
- 长代码
```csharp
 public IActionResult Details(int id) {
            Student1 student = _stuentRepositorys.GetStudentById(id);
            if (student==null) {
                Response.StatusCode = 404;
                return View("NotFound",id);
            }
            Student1 model = student;
            //ViewData["student"] = model;
            return View(model);
        }
```
# 表格
 | header| header |
 | ------ | ------ |
 | cell | cell |
 | cell | cell |
 - [ ] aspx

了解更多
