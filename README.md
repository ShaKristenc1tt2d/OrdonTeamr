# [avalidate.js]：为[APICloud](http://www.apicloud.com/)表单验证而生，但不仅仅限于此！

* 作者：新生帝
* QQ：8020292
* QQ交流群：18863883
* 技术支持：[中山赢友网络科技有限公司](http://www.winu.net/)

* [APICloud](http://www.apicloud.com/)是一个非常好的一个APP开发平台！[APICloud官网](http://www.apicloud.com/)
* [论坛回帖地址](http://community.apicloud.com/bbs/forum.php?mod=viewthread&tid=17310&page=1&extra=#pid95308) 

## 来先看看例子

* [实例一](http://availdate.oschina.mopaasapp.com/)
* [实例二](http://availdate.oschina.mopaasapp.com/demo2.html)
* [实例三](http://availdate.oschina.mopaasapp.com/demo3.html)
* [实例四](http://availdate.oschina.mopaasapp.com/demo4.html)
* [实例五](http://availdate.oschina.mopaasapp.com/demo5.html)


## 更新记录

```
### 2015年11月07日  availdate-1.0.1.js 更新细节：
* [新增] 验证成功之后返回序列化对象
* [新增] idcard 标识符，支持身份证验证
* [新增] time 标识符，支持时间格式验证
* [新增] tm 标识符，支持手机或固话的验证
* [新增] t 标识符，支持固话的验证
* [修复] 修复验证只获取到子类的bug，无法获取子代所有元素
* [修复] 修复一系列bug

### 2015年11月06日   availdate-1.0.0.js 版本正式发布：
* [新增] 整个项目基础原型
```

非常感谢流浪男版主带给我们非常好的[APICloud](http://www.auicss.com/)布局框架，让我们的开发速度再一次的升华！但是，想更快的开发，更省代码吗？availdate.js能帮到你！

## availdate.js是什么呢？


我们在开发的过程中，经常遇到很多需要用户填写的表单，每次都需要写非常庞大的表单验证脚本，试想一下，如果需要客户填写100个表单，那验证脚本岂不是吓死宝宝了，而且会非常的占用开发时间！时势造英雄，这时候，availdate.js就来了！

availdate.js是一个纯javascript编写的一个验证脚本插件，不依赖于任何第三方框架，直接在页面中使用即可，她具有跨平台，小巧，拓展性极强和完全开源等的特点！你只需要短短的代码，甚至不需要代码就可以实现完整的验证操作了，她还内置了大量的常用的验证库，大大的提升了我们的开发速度。

availdate.js第一个版本是本人花了3个多小时编写的，可能在使用过程成会出现遗漏或者未能考虑到的bug，请及时反馈，定当全力修复bug。

[APICloud](http://www.apicloud.com/)会越来越美好，因为有他们，你们，我们的共同努力！让我们一起见证一个孩子的创世之路吧！


### availdate.js自定义标签属性：


* `data-rule`：必填，这个属性是整个验证插件的基础。注意：需要验证的插件必须填写该属性，但除了指定data-sync属性以外。
* `data-nullmsg`： 选填，当表单为空的时候提示信息。
* `data-errmsg`	： 选填，当表单验证失败的时候提示信息。
* `data-sucmsg`：选填，当表单执行成功的时候提示信息。
* `data-sync`：选填，同步验证，一般用于密码的验证。比如，第一次输入密码之后，然后第二次密码需要和第一次输入密码进行同步验证。
* `data-haved`：选填，跳过为空验证，只当有值的时候才会执行验证。


### availdate.js内置默认验证规则：


* `*`：必填，不能为空。例子：`data-rule="*"`
* `*6-16`：必填，不能为空，且必须是6到16个字符。例子：`data-rule="*3-12"`，`data-rule="*5-10"`。分别表示：必填，3到12个字符；必填，5到10个字符。
* `n`：必填，不能为空，且必须是正整数。例子：`data-rule="n"`
* `n6-16`：必填，不能为空，且必须是6到16个字符例子：`data-rule="n3-12"`
* `s`：必填，不能为空，且不能包含特殊字符的字符串。例子：`data-rule="s"`
* `s6-16`：必填，不能为空，且必须是6到16位的非包含特殊字符的字符串。例子：`data-rule="s6-16"`
* `p`：必填，不能为空，且必须是正确的邮政编码。例子：`data-rule="p"`
* `m`：必填，不能为空，且必须是正确的手机号码。例子：`data-rule="m"`
* `e`：必填，不能为空，且必须是电子邮箱。例子：`data-rule="e"`
* `url`：必填，不能为空，且必须是网址格式。例子：`data-rule="url"`
* `date`：必填，不能为空，且必须是日期格式。例子：`data-rule="date"`
* `zh`：必填，不能为空，且必须是中文。例子：`data-rule="zh"`
* `dword`：必填，不能为空，且必须填写双字节字符。例子：`data-rule="dword"`
* `money`：必填，不能为空，且必须是金额类型。例子：`data-rule="money"`
* `ipv4`：必填，不能为空，且必须是IPv4地址。例子：`data-rule="ipv4"`
* `ipv6`：必填，不能为空，且必须是IPv6地址。例子：`data-rule="ipv6"`
* `num`：必填，不能为空，必须是数值类型，例如正整数，正浮点数，小数。例子：`data-rule="num"`
* `qq`：必填，不能为空，必须是qq号码。例子：`data-rule="qq"`
* `idcard`：必填，不能为空，必须是身份证号码。例子：`data-rule="idcard"`
* `time`：必填，不能为空，必须是时间格式号码，如：10:23:60。例子：`data-rule="time"`
* `t`：必填，不能为空，必须是固话号码，如：0760-88809987。例子：`data-rule="t"`
* `tm`：必填，不能为空，必须是手机或者固话号码，如：18676265646，0760-88809987。例子：`data-rule="tm"`


### 还不够？

如果上面的还不能满足你，不用担心，data-rule也支持万能的正则表达式，如：

```html
data-rule="/\w{3,6}/i"    表示3-6位字符
data-rule="/^\d$/"       只允许一个数字
```

注意：如果data-rule传入的是正则表达式，则必须用 / / 包住。

### 我想和默认标识符一样，替代正则表达式，行不行？当然行！

```html
ac.addRule({
            // 支持固话和手机的验证
            "tm": /(^[0-9]{3,4}\-[0-9]{3,8}$)|(^[0-9]{3,8}$)|(^\([0-9]{3,4}\)[0-9]{3,8}$)|(^0{0,1}13[0-9]{9}$)/
});
```

这样就可以通过 data-rule="tm" 来验证手机和固话了。

### availdate.js公开方法

#### ac.form(params);	描述：所有需要验证的区域都需要调用这个方法

```html
params参数说明：
{
    area: "body", // 需要验证的区域，支持标签名称，id，class选择器，推荐id或class
    btn: "",  // 点击触发验证的按钮 ，支持标签名称，id，class选择器
    startCheck: function () {   
        // 开始检查执行函数，一般用户动画效果，比如加载中，提交中，验证中。
    },
    singleSuccess: function (e, msg) {    
       // 单个表单验证成功执行函数，可以通过这个方法写一些小特效或者处理方法
       // e：当前验证的对象，msg：提示信息。
    }
    singleError: function (e, msg) { 
        // 单个表单验证失败执行函数
        // e：当前验证的对象，msg：提示信息。

        alert(msg);
    },
    endSuccess: function (data) {  // 全部验证成功执行函数
		// data 返回序列化的参数
    }
}
```

#### ac.addRule(params);	描述：拓展默认data-rule标识符，拓展之后，可直接使用标识符代表该正则表达式

```html
  params参数说明：
  {
      // 属性名称表示标识符，属性值表示正则表达式，可以设置多个。
      "tm":/((15)\d{9})|((13)\d{9})|((18)\d{9})|(0[1-9]{2,3}\-?[1-9]{6,7})/i     
  }

```


###  介绍了那么多，那该如何在项目中使用呢？

#### 1）基本使用

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--引入插件-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>必填验证：data-rule="*"</h3>
        姓名：   <input type="text" data-rule="*" data-nullmsg="姓名不能为空" data-errmsg="验证失败" data-sucmsg="" />



        <h3>指定字符数：data-rule="*3-5"，标识只能输入3到5个字符</h3>
        姓名2：   <input type="text" data-rule="*3-5" data-nullmsg="姓名2不能为空" data-errmsg="姓名2只能是3到5个字符" data-sucmsg="验证成功" />



        <h3>验证正整数：data-rule="n"</h3>
        年龄：   <input type="text" data-rule="n" data-nullmsg="年龄不能为空" data-errmsg="年龄只能是正整数" data-sucmsg="验证成功" />



        <h3>验证正整数：data-rule="n3-6"，只能输入3到6位正整数</h3>
        个数：   <input type="text" data-rule="n3-6" data-nullmsg="个数不能为空" data-errmsg="只能输入3-6位正整数" data-sucmsg="验证成功" />



        <h3>只能输入字符串，不能输入特殊字符：data-rule="s"</h3>
        昵称：   <input type="text" data-rule="s" data-nullmsg="昵称不能为空" data-errmsg="昵称包含特殊字符" data-sucmsg="验证成功" />



        <h3>只能输入字符串，不能输入特殊字符：data-rule="s3-6"，只能输入不包含特殊字符的字符串，并且在3到6个字符之间</h3>
        昵称2：   <input type="text" data-rule="s3-6" data-nullmsg="昵称2不能为空" data-errmsg="昵称2验证失败，不能包含特殊字符，或者只能是3到6位" data-sucmsg="验证成功" />



        <h3>验证邮政编码：data-rule="p"</h3>
        邮政编码：   <input type="text" data-rule="p" data-nullmsg="邮政编码不能为空" data-errmsg="你输入的不是一个正确的邮政编码" data-sucmsg="验证成功" />



        <h3>验证手机号码：data-rule="m"</h3>
        手机号码：   <input type="text" data-rule="m" data-nullmsg="手机号码不能为空" data-errmsg="你输入的不是一个手机号码" data-sucmsg="验证成功" />


        <h3>验证电子邮件：data-rule="e"</h3>
        电子邮件：   <input type="text" data-rule="e" data-nullmsg="电子邮件不能为空" data-errmsg="你输入的不是一个电子邮件" data-sucmsg="验证成功" />



        <h3>验证是否是一个网址：data-rule="url"</h3>
        网址：   <input type="text" data-rule="url" data-nullmsg="网址不能为空" data-errmsg="你输入的不是一个网址" data-sucmsg="验证成功" />



        <h3>验证是否是日期格式：data-rule="date"，支持各种格式的日期格式</h3>
        出生日期：   <input type="text" data-rule="date" data-nullmsg="出生日期为空" data-errmsg="你输入的日期格式不正确" data-sucmsg="验证成功" />



        <h3>验证是否是中文：data-rule="zh"</h3>
        中文名称：   <input type="text" data-rule="zh" data-nullmsg="中文名称不能为空" data-errmsg="你输入的不是一个全中文" data-sucmsg="验证成功" />



        <h3>验证是否是中文：data-rule="/^[\u4e00-\u9fa5]{3,6}$/"，只能输入3到6个中文名称，<font style="color:#f00">支持万能的正则表达式</font></h3>
        中文名称：   <input type="text" data-rule="/^[\u4e00-\u9fa5]{3,6}$/" data-nullmsg="中文名称不能为空" data-errmsg="只能输入3到6个中文字" data-sucmsg="验证成功" />



        <h3>验证金钱格式：data-rule="money"</h3>
        你的工资是多少：   <input type="text" data-rule="money" data-nullmsg="工资不能为空" data-errmsg="你输入的不是一个金钱格式" data-sucmsg="验证成功" />



        <h3>验证数值类型：data-rule="num"，支持小数，整数</h3>
        你的身高：   <input type="text" data-rule="num" data-nullmsg="身高不能为空" data-errmsg="你输入的不是一个数值类型" data-sucmsg="验证成功" />



        <h3>你的性别：data-rule="*"</h3>
        性别：   <input type="radio" name="gender" data-rule="*" data-nullmsg="必须选择一个性别" data-sucmsg="验证成功" value="男" /> 男<input type="radio" name="gender" data-rule="*" data-nullmsg="必须选择一个性别" data-sucmsg="验证成功" value="女" /> 女



        <h3>你的兴趣爱好：data-rule="*"</h3>
        性别：   <input type="checkbox" name="like" data-rule="*" data-nullmsg="至少选一个" data-sucmsg="验证成功" value="篮球" /> 篮球 <input type="checkbox" name="like" data-rule="*" data-nullmsg="至少选一个" data-sucmsg="验证成功" value="足球" /> 足球<input type="checkbox" name="like" data-rule="*" data-nullmsg="至少选一个" data-sucmsg="验证成功" value="羽毛球" /> 羽毛球



        <h3>你是基佬吗？：data-rule="*"</h3>
        是否基佬？：   <select data-rule="*">
            <option value="">请选择</option>
            <option value="是">是</option>
            <option value="不是">不是</option>
        </select>



        <br />
        <br />
        <input type="button" id="btn" value="提交" />
    </form>
    <script type="text/javascript">

        // 对，就这么简单就初始化了。
        ac.form({
            area: "#frm",   // 验证区域，支持标签，id，class，推荐使用id或者class
            btn: "#btn",     // 触发验证的按钮或者元素，支持标签，id，class，推荐使用id或者class
            endSuccess: function (data) {
                  alert("全部验证成功啦！！！！！！" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```

#### 2）高级使用

##### 1、自定义验证错误提示，主要是编写singleError方法

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--引入插件-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>必填验证：data-rule="*"</h3>
        姓名：   <input type="text" data-rule="*" data-nullmsg="姓名不能为空" data-errmsg="验证失败" data-sucmsg="" />

        <br />
        <br />
        <input type="button" id="btn" value="提交" />
    </form>
    <script type="text/javascript">

        // 对，就这么简单就初始化了。
        ac.form({
            area: "#frm",   // 验证区域，支持标签，id，class，推荐使用id或者class
            btn: "#btn",     // 触发验证的按钮或者元素，支持标签，id，class，推荐使用id或者class
            singleError: function (e, msg) {
                // 自定义弹窗格式###############
                alert("我是自定义弹窗格式：错误消息：" + msg);
            },
            endSuccess: function (data) {
                  alert("全部验证成功啦！！！！！！" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```

##### 2、每一个表单元素验证成功之后执行自定义函数，主要是编写singleSuccess方法

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--引入插件-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>必填验证：data-rule="*"</h3>
        姓名：   <input type="text" data-rule="*" data-nullmsg="姓名不能为空" data-errmsg="验证失败" data-sucmsg="" />

        <br />
        <br />
        <input type="button" id="btn" value="提交" />
    </form>
    <script type="text/javascript">

        // 对，就这么简单就初始化了。
        ac.form({
            area: "#frm",   // 验证区域，支持标签，id，class，推荐使用id或者class
            btn: "#btn",     // 触发验证的按钮或者元素，支持标签，id，class，推荐使用id或者class
            singleError: function (e, msg) {
                // 自定义弹窗格式###############
                alert("我是自定义弹窗格式：错误消息：" + msg);
            },
            singleSuccess: function (e, msg) {
                // 验证单个成功之后提示信息
                alert("我自己通过验证了！别人我不知道！");
            },
            endSuccess: function (data) {
                  alert("全部验证成功啦！！！！！！" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```

##### 3、在表单验证之前执行自定义函数，主要是编写startCheck方法

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--引入插件-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>必填验证：data-rule="*"</h3>
        姓名：   <input type="text" data-rule="*" data-nullmsg="姓名不能为空" data-errmsg="验证失败" data-sucmsg="" />

        <br />
        <br />
        <input type="button" id="btn" value="提交" />
    </form>
    <script type="text/javascript">

        // 对，就这么简单就初始化了。
        ac.form({
            area: "#frm",   // 验证区域，支持标签，id，class，推荐使用id或者class
            btn: "#btn",     // 触发验证的按钮或者元素，支持标签，id，class，推荐使用id或者class
            startCheck: function () {
                // 自定义验证之前执行函数
                alert("开始验证啦！一般用于加载！");
            },
            singleError: function (e, msg) {
                // 自定义弹窗格式###############
                alert("我是自定义弹窗格式：错误消息：" + msg);
            },
            singleSuccess: function (e, msg) {
                // 验证单个成功之后提示信息
                alert("我自己通过验证了！别人我不知道！");
            },
            endSuccess: function (data) {
                  alert("全部验证成功啦！！！！！！" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```

##### 4、自定义data-rule标识符，比如验证手机或固话：data-rule="tm"   本身是没有这个标识的

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--引入插件-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>手机或者固话：data-rule="tm"  我是自定义验证规则标识的，本来没有tm的标识，tm标识固话或者手机</h3>
        手机或者固话：   <input type="text" data-rule="tm" data-nullmsg="手机或固话不能为空" data-errmsg="你输入的不是一个手机或者固话" data-sucmsg="" />

        <br />
        <br />
        <input type="button" id="btn" value="提交" />
    </form>
    <script type="text/javascript">
        // 自定义标识规则
        ac.addRule({
            "tm": /((15)\d{9})|((13)\d{9})|((18)\d{9})|(0[1-9]{2,3}\-?[1-9]{6,7})/i
        });

        // 对，就这么简单就初始化了。
        ac.form({
            area: "#frm",   // 验证区域，支持标签，id，class，推荐使用id或者class
            btn: "#btn",
           endSuccess: function (data) {
                  alert("全部验证成功啦！！！！！！" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```


#### 3）还可以这样用！

##### 1、比如判断两次密码输入是否一样，主要用到data-sync="同步的name名称"，同步验证

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--引入插件-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>验证两次输入密码是否一致：data-rule="s3-10"  ，注意是通过data-sync="需要同步验证的name值"，这时候必须指定name值了</h3>
        密码一：   <input type="password" name="pwd" data-rule="s3-10" data-nullmsg="请输入密码" data-errmsg="你输入的密码不正确" data-sucmsg="" />
        <br />
        <h3>如果添加了data-sync属性，可以不写data-rule了。</h3>
        密码二：   <input type="password" name="pwd2" data-nullmsg="请再次输入密码" data-errmsg="你两次输入密码不正确" data-sucmsg="" data-sync="pwd" />
        <br />
        <br />
        <input type="button" id="btn" value="提交" />
    </form>
    <script type="text/javascript">

        // 对，就这么简单就初始化了。
        ac.form({
            area: "#frm",   // 验证区域，支持标签，id，class，推荐使用id或者class
            btn: "#btn",
            endSuccess: function (data) {
                  alert("全部验证成功啦！！！！！！" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```

##### 2、如果不填，则忽略验证，如果填写则执行验证，主要用到data-haved="true"属性

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--引入插件-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>必须输入3到6个字符：data-rule="*3-6"，如果添加了data-haved="true"之后，就不执行为空验证了，只有填写值的时候才执行验证</h3>
        姓名：   <input type="text" data-rule="*3-6" data-nullmsg="姓名不能为空" data-errmsg="必须是3到6个字符" data-sucmsg="" data-haved="true" />

        <br />
        <br />
        <input type="button" id="btn" value="提交" />
    </form>
    <script type="text/javascript">

        // 对，就这么简单就初始化了。
        ac.form({
            area: "#frm",   // 验证区域，支持标签，id，class，推荐使用id或者class
            btn: "#btn",
            endSuccess: function (data) {
                  alert("全部验证成功啦！！！！！！" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```

* 更多例子由你来发现！！！

* availdate.js为[APICloud](http://www.apicloud.com/)而生，但不仅仅限于此！

* availdate.js开源地址：[Github](http://git.oschina.net/winu.net/availdate.js)

* QQ交流群：18863883

* 技术支持：[中山赢友网络科技有限公司](http://www.winu.net/)