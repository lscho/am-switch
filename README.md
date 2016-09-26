## Amaze ui 开关插件

[demo地址](https://lscho.github.io/am-switch/docs/demo.html "demo地址")

###使用说明

**1. 获取**

- 直接下载：[下载地址](https://github.com/lscho/am-switch/archive/master.zip)

**2. 引入文件**
依赖于amaze ui框架，需要先引入框架文件
```javascript
    <link rel="stylesheet" type="text/css" href="../dist/amazeui.min.css">
    <link rel="stylesheet" type="text/css" href="../dist/amazeui.switch.css">
    <script type="text/javascript" src="../dist/jquery.min.js"></script>
    <script type="text/javascript" src="../dist/amazeui.min.js"></script>
    <script type="text/javascript" src="../dist/amazeui.switch.js"></script>
```

**3. 开始使用**

```html
    <input type="checkbox" class="am-switch" />
```

##文档

**1. 普通示例**

```html
          <input type="checkbox" class="am-switch" />
          <input type="checkbox" class="am-switch" checked />
```

**2. 简洁模式**

```html
          <input type="checkbox" class="am-switch am-switch-mini" />
          <input type="checkbox" class="am-switch am-switch-mini" checked />
```

**3. 多主题**

```html
          <input type="checkbox" class="am-switch am-switch-default" checked />
          <input type="checkbox" class="am-switch am-switch-secondary" checked />
          <input type="checkbox" class="am-switch am-switch-success" checked />
          <input type="checkbox" class="am-switch am-switch-warning" checked />
          <input type="checkbox" class="am-switch am-switch-danger" checked /> 
```

**4. 形状**

```html
<input type="checkbox" class="am-switch am-switch-default" checked />
<input type="checkbox" class="am-switch am-round am-switch-default" checked />
```

**5.异步渲染**

$(element).switch();

```html
        <button class="am-btn am-btn-default" id="insert">插入</button>   
        <div class="am-g" id="content" style="margin-top:40px;">

        </div>
```

```javascript
        <script type="text/javascript">
          $(function(){
            $("#insert").click(function(){
              $switch=$('<input type="checkbox" class="am-switch am-switch-default" checked />');
              $("#content").append($switch);
              $switch.switch();
            });
          });
        </script>
```
##License

MIT © 2015 - 2016 AllMobilize Inc.