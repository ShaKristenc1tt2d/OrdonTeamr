# [avalidate.js]��Ϊ[APICloud](http://www.apicloud.com/)����֤�����������������ڴˣ�

* ���ߣ�������
* QQ��8020292
* QQ����Ⱥ��18863883
* ����֧�֣�[��ɽӮ������Ƽ����޹�˾](http://www.winu.net/)

* [APICloud](http://www.apicloud.com/)��һ���ǳ��õ�һ��APP����ƽ̨��[APICloud����](http://www.apicloud.com/)
* [��̳������ַ](http://community.apicloud.com/bbs/forum.php?mod=viewthread&tid=17310&page=1&extra=#pid95308) 

## ���ȿ�������

* [ʵ��һ](http://availdate.oschina.mopaasapp.com/)
* [ʵ����](http://availdate.oschina.mopaasapp.com/demo2.html)
* [ʵ����](http://availdate.oschina.mopaasapp.com/demo3.html)
* [ʵ����](http://availdate.oschina.mopaasapp.com/demo4.html)
* [ʵ����](http://availdate.oschina.mopaasapp.com/demo5.html)


## ���¼�¼

```
### 2015��11��07��  availdate-1.0.1.js ����ϸ�ڣ�
* [����] ��֤�ɹ�֮�󷵻����л�����
* [����] idcard ��ʶ����֧�����֤��֤
* [����] time ��ʶ����֧��ʱ���ʽ��֤
* [����] tm ��ʶ����֧���ֻ���̻�����֤
* [����] t ��ʶ����֧�ֹ̻�����֤
* [�޸�] �޸���ֻ֤��ȡ�������bug���޷���ȡ�Ӵ�����Ԫ��
* [�޸�] �޸�һϵ��bug

### 2015��11��06��   availdate-1.0.0.js �汾��ʽ������
* [����] ������Ŀ����ԭ��
```

�ǳ���л�����а����������Ƿǳ��õ�[APICloud](http://www.auicss.com/)���ֿ�ܣ������ǵĿ����ٶ���һ�ε����������ǣ������Ŀ�������ʡ������availdate.js�ܰﵽ�㣡

## availdate.js��ʲô�أ�


�����ڿ����Ĺ����У����������ܶ���Ҫ�û���д�ı���ÿ�ζ���Ҫд�ǳ��Ӵ�ı���֤�ű�������һ�£������Ҫ�ͻ���д100����������֤�ű��������������ˣ����һ�ǳ���ռ�ÿ���ʱ�䣡ʱ����Ӣ�ۣ���ʱ��availdate.js�����ˣ�

availdate.js��һ����javascript��д��һ����֤�ű���������������κε�������ܣ�ֱ����ҳ����ʹ�ü��ɣ������п�ƽ̨��С�ɣ���չ�Լ�ǿ����ȫ��Դ�ȵ��ص㣡��ֻ��Ҫ�̶̵Ĵ��룬��������Ҫ����Ϳ���ʵ����������֤�����ˣ����������˴����ĳ��õ���֤�⣬�������������ǵĿ����ٶȡ�

availdate.js��һ���汾�Ǳ��˻���3����Сʱ��д�ģ�������ʹ�ù��̳ɻ������©����δ�ܿ��ǵ���bug���뼰ʱ����������ȫ���޸�bug��

[APICloud](http://www.apicloud.com/)��Խ��Խ���ã���Ϊ�����ǣ����ǣ����ǵĹ�ͬŬ����������һ���֤һ�����ӵĴ���֮·�ɣ�


### availdate.js�Զ����ǩ���ԣ�


* `data-rule`��������������������֤����Ļ�����ע�⣺��Ҫ��֤�Ĳ��������д�����ԣ�������ָ��data-sync�������⡣
* `data-nullmsg`�� ѡ�����Ϊ�յ�ʱ����ʾ��Ϣ��
* `data-errmsg`	�� ѡ�������֤ʧ�ܵ�ʱ����ʾ��Ϣ��
* `data-sucmsg`��ѡ�����ִ�гɹ���ʱ����ʾ��Ϣ��
* `data-sync`��ѡ�ͬ����֤��һ�������������֤�����磬��һ����������֮��Ȼ��ڶ���������Ҫ�͵�һ�������������ͬ����֤��
* `data-haved`��ѡ�����Ϊ����֤��ֻ����ֵ��ʱ��Ż�ִ����֤��


### availdate.js����Ĭ����֤����


* `*`���������Ϊ�ա����ӣ�`data-rule="*"`
* `*6-16`���������Ϊ�գ��ұ�����6��16���ַ������ӣ�`data-rule="*3-12"`��`data-rule="*5-10"`���ֱ��ʾ�����3��12���ַ������5��10���ַ���
* `n`���������Ϊ�գ��ұ����������������ӣ�`data-rule="n"`
* `n6-16`���������Ϊ�գ��ұ�����6��16���ַ����ӣ�`data-rule="n3-12"`
* `s`���������Ϊ�գ��Ҳ��ܰ��������ַ����ַ��������ӣ�`data-rule="s"`
* `s6-16`���������Ϊ�գ��ұ�����6��16λ�ķǰ��������ַ����ַ��������ӣ�`data-rule="s6-16"`
* `p`���������Ϊ�գ��ұ�������ȷ���������롣���ӣ�`data-rule="p"`
* `m`���������Ϊ�գ��ұ�������ȷ���ֻ����롣���ӣ�`data-rule="m"`
* `e`���������Ϊ�գ��ұ����ǵ������䡣���ӣ�`data-rule="e"`
* `url`���������Ϊ�գ��ұ�������ַ��ʽ�����ӣ�`data-rule="url"`
* `date`���������Ϊ�գ��ұ��������ڸ�ʽ�����ӣ�`data-rule="date"`
* `zh`���������Ϊ�գ��ұ��������ġ����ӣ�`data-rule="zh"`
* `dword`���������Ϊ�գ��ұ�����д˫�ֽ��ַ������ӣ�`data-rule="dword"`
* `money`���������Ϊ�գ��ұ����ǽ�����͡����ӣ�`data-rule="money"`
* `ipv4`���������Ϊ�գ��ұ�����IPv4��ַ�����ӣ�`data-rule="ipv4"`
* `ipv6`���������Ϊ�գ��ұ�����IPv6��ַ�����ӣ�`data-rule="ipv6"`
* `num`���������Ϊ�գ���������ֵ���ͣ�����������������������С�������ӣ�`data-rule="num"`
* `qq`���������Ϊ�գ�������qq���롣���ӣ�`data-rule="qq"`
* `idcard`���������Ϊ�գ����������֤���롣���ӣ�`data-rule="idcard"`
* `time`���������Ϊ�գ�������ʱ���ʽ���룬�磺10:23:60�����ӣ�`data-rule="time"`
* `t`���������Ϊ�գ������ǹ̻����룬�磺0760-88809987�����ӣ�`data-rule="t"`
* `tm`���������Ϊ�գ��������ֻ����߹̻����룬�磺18676265646��0760-88809987�����ӣ�`data-rule="tm"`


### ��������

�������Ļ����������㣬���õ��ģ�data-ruleҲ֧�����ܵ�������ʽ���磺

```html
data-rule="/\w{3,6}/i"    ��ʾ3-6λ�ַ�
data-rule="/^\d$/"       ֻ����һ������
```

ע�⣺���data-rule�������������ʽ��������� / / ��ס��

### �����Ĭ�ϱ�ʶ��һ�������������ʽ���в��У���Ȼ�У�

```html
ac.addRule({
            // ֧�ֹ̻����ֻ�����֤
            "tm": /(^[0-9]{3,4}\-[0-9]{3,8}$)|(^[0-9]{3,8}$)|(^\([0-9]{3,4}\)[0-9]{3,8}$)|(^0{0,1}13[0-9]{9}$)/
});
```

�����Ϳ���ͨ�� data-rule="tm" ����֤�ֻ��͹̻��ˡ�

### availdate.js��������

#### ac.form(params);	������������Ҫ��֤��������Ҫ�����������

```html
params����˵����
{
    area: "body", // ��Ҫ��֤������֧�ֱ�ǩ���ƣ�id��classѡ�������Ƽ�id��class
    btn: "",  // ���������֤�İ�ť ��֧�ֱ�ǩ���ƣ�id��classѡ����
    startCheck: function () {   
        // ��ʼ���ִ�к�����һ���û�����Ч������������У��ύ�У���֤�С�
    },
    singleSuccess: function (e, msg) {    
       // ��������֤�ɹ�ִ�к���������ͨ���������дһЩС��Ч���ߴ�����
       // e����ǰ��֤�Ķ���msg����ʾ��Ϣ��
    }
    singleError: function (e, msg) { 
        // ��������֤ʧ��ִ�к���
        // e����ǰ��֤�Ķ���msg����ʾ��Ϣ��

        alert(msg);
    },
    endSuccess: function (data) {  // ȫ����֤�ɹ�ִ�к���
		// data �������л��Ĳ���
    }
}
```

#### ac.addRule(params);	��������չĬ��data-rule��ʶ������չ֮�󣬿�ֱ��ʹ�ñ�ʶ�������������ʽ

```html
  params����˵����
  {
      // �������Ʊ�ʾ��ʶ��������ֵ��ʾ������ʽ���������ö����
      "tm":/((15)\d{9})|((13)\d{9})|((18)\d{9})|(0[1-9]{2,3}\-?[1-9]{6,7})/i     
  }

```


###  ��������ô�࣬�Ǹ��������Ŀ��ʹ���أ�

#### 1������ʹ��

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--������-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>������֤��data-rule="*"</h3>
        ������   <input type="text" data-rule="*" data-nullmsg="��������Ϊ��" data-errmsg="��֤ʧ��" data-sucmsg="" />



        <h3>ָ���ַ�����data-rule="*3-5"����ʶֻ������3��5���ַ�</h3>
        ����2��   <input type="text" data-rule="*3-5" data-nullmsg="����2����Ϊ��" data-errmsg="����2ֻ����3��5���ַ�" data-sucmsg="��֤�ɹ�" />



        <h3>��֤��������data-rule="n"</h3>
        ���䣺   <input type="text" data-rule="n" data-nullmsg="���䲻��Ϊ��" data-errmsg="����ֻ����������" data-sucmsg="��֤�ɹ�" />



        <h3>��֤��������data-rule="n3-6"��ֻ������3��6λ������</h3>
        ������   <input type="text" data-rule="n3-6" data-nullmsg="��������Ϊ��" data-errmsg="ֻ������3-6λ������" data-sucmsg="��֤�ɹ�" />



        <h3>ֻ�������ַ������������������ַ���data-rule="s"</h3>
        �ǳƣ�   <input type="text" data-rule="s" data-nullmsg="�ǳƲ���Ϊ��" data-errmsg="�ǳư��������ַ�" data-sucmsg="��֤�ɹ�" />



        <h3>ֻ�������ַ������������������ַ���data-rule="s3-6"��ֻ�����벻���������ַ����ַ�����������3��6���ַ�֮��</h3>
        �ǳ�2��   <input type="text" data-rule="s3-6" data-nullmsg="�ǳ�2����Ϊ��" data-errmsg="�ǳ�2��֤ʧ�ܣ����ܰ��������ַ�������ֻ����3��6λ" data-sucmsg="��֤�ɹ�" />



        <h3>��֤�������룺data-rule="p"</h3>
        �������룺   <input type="text" data-rule="p" data-nullmsg="�������벻��Ϊ��" data-errmsg="������Ĳ���һ����ȷ����������" data-sucmsg="��֤�ɹ�" />



        <h3>��֤�ֻ����룺data-rule="m"</h3>
        �ֻ����룺   <input type="text" data-rule="m" data-nullmsg="�ֻ����벻��Ϊ��" data-errmsg="������Ĳ���һ���ֻ�����" data-sucmsg="��֤�ɹ�" />


        <h3>��֤�����ʼ���data-rule="e"</h3>
        �����ʼ���   <input type="text" data-rule="e" data-nullmsg="�����ʼ�����Ϊ��" data-errmsg="������Ĳ���һ�������ʼ�" data-sucmsg="��֤�ɹ�" />



        <h3>��֤�Ƿ���һ����ַ��data-rule="url"</h3>
        ��ַ��   <input type="text" data-rule="url" data-nullmsg="��ַ����Ϊ��" data-errmsg="������Ĳ���һ����ַ" data-sucmsg="��֤�ɹ�" />



        <h3>��֤�Ƿ������ڸ�ʽ��data-rule="date"��֧�ָ��ָ�ʽ�����ڸ�ʽ</h3>
        �������ڣ�   <input type="text" data-rule="date" data-nullmsg="��������Ϊ��" data-errmsg="����������ڸ�ʽ����ȷ" data-sucmsg="��֤�ɹ�" />



        <h3>��֤�Ƿ������ģ�data-rule="zh"</h3>
        �������ƣ�   <input type="text" data-rule="zh" data-nullmsg="�������Ʋ���Ϊ��" data-errmsg="������Ĳ���һ��ȫ����" data-sucmsg="��֤�ɹ�" />



        <h3>��֤�Ƿ������ģ�data-rule="/^[\u4e00-\u9fa5]{3,6}$/"��ֻ������3��6���������ƣ�<font style="color:#f00">֧�����ܵ�������ʽ</font></h3>
        �������ƣ�   <input type="text" data-rule="/^[\u4e00-\u9fa5]{3,6}$/" data-nullmsg="�������Ʋ���Ϊ��" data-errmsg="ֻ������3��6��������" data-sucmsg="��֤�ɹ�" />



        <h3>��֤��Ǯ��ʽ��data-rule="money"</h3>
        ��Ĺ����Ƕ��٣�   <input type="text" data-rule="money" data-nullmsg="���ʲ���Ϊ��" data-errmsg="������Ĳ���һ����Ǯ��ʽ" data-sucmsg="��֤�ɹ�" />



        <h3>��֤��ֵ���ͣ�data-rule="num"��֧��С��������</h3>
        �����ߣ�   <input type="text" data-rule="num" data-nullmsg="��߲���Ϊ��" data-errmsg="������Ĳ���һ����ֵ����" data-sucmsg="��֤�ɹ�" />



        <h3>����Ա�data-rule="*"</h3>
        �Ա�   <input type="radio" name="gender" data-rule="*" data-nullmsg="����ѡ��һ���Ա�" data-sucmsg="��֤�ɹ�" value="��" /> ��<input type="radio" name="gender" data-rule="*" data-nullmsg="����ѡ��һ���Ա�" data-sucmsg="��֤�ɹ�" value="Ů" /> Ů



        <h3>�����Ȥ���ã�data-rule="*"</h3>
        �Ա�   <input type="checkbox" name="like" data-rule="*" data-nullmsg="����ѡһ��" data-sucmsg="��֤�ɹ�" value="����" /> ���� <input type="checkbox" name="like" data-rule="*" data-nullmsg="����ѡһ��" data-sucmsg="��֤�ɹ�" value="����" /> ����<input type="checkbox" name="like" data-rule="*" data-nullmsg="����ѡһ��" data-sucmsg="��֤�ɹ�" value="��ë��" /> ��ë��



        <h3>���ǻ����𣿣�data-rule="*"</h3>
        �Ƿ���У���   <select data-rule="*">
            <option value="">��ѡ��</option>
            <option value="��">��</option>
            <option value="����">����</option>
        </select>



        <br />
        <br />
        <input type="button" id="btn" value="�ύ" />
    </form>
    <script type="text/javascript">

        // �ԣ�����ô�򵥾ͳ�ʼ���ˡ�
        ac.form({
            area: "#frm",   // ��֤����֧�ֱ�ǩ��id��class���Ƽ�ʹ��id����class
            btn: "#btn",     // ������֤�İ�ť����Ԫ�أ�֧�ֱ�ǩ��id��class���Ƽ�ʹ��id����class
            endSuccess: function (data) {
                  alert("ȫ����֤�ɹ���������������" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```

#### 2���߼�ʹ��

##### 1���Զ�����֤������ʾ����Ҫ�Ǳ�дsingleError����

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--������-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>������֤��data-rule="*"</h3>
        ������   <input type="text" data-rule="*" data-nullmsg="��������Ϊ��" data-errmsg="��֤ʧ��" data-sucmsg="" />

        <br />
        <br />
        <input type="button" id="btn" value="�ύ" />
    </form>
    <script type="text/javascript">

        // �ԣ�����ô�򵥾ͳ�ʼ���ˡ�
        ac.form({
            area: "#frm",   // ��֤����֧�ֱ�ǩ��id��class���Ƽ�ʹ��id����class
            btn: "#btn",     // ������֤�İ�ť����Ԫ�أ�֧�ֱ�ǩ��id��class���Ƽ�ʹ��id����class
            singleError: function (e, msg) {
                // �Զ��嵯����ʽ###############
                alert("�����Զ��嵯����ʽ��������Ϣ��" + msg);
            },
            endSuccess: function (data) {
                  alert("ȫ����֤�ɹ���������������" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```

##### 2��ÿһ����Ԫ����֤�ɹ�֮��ִ���Զ��庯������Ҫ�Ǳ�дsingleSuccess����

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--������-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>������֤��data-rule="*"</h3>
        ������   <input type="text" data-rule="*" data-nullmsg="��������Ϊ��" data-errmsg="��֤ʧ��" data-sucmsg="" />

        <br />
        <br />
        <input type="button" id="btn" value="�ύ" />
    </form>
    <script type="text/javascript">

        // �ԣ�����ô�򵥾ͳ�ʼ���ˡ�
        ac.form({
            area: "#frm",   // ��֤����֧�ֱ�ǩ��id��class���Ƽ�ʹ��id����class
            btn: "#btn",     // ������֤�İ�ť����Ԫ�أ�֧�ֱ�ǩ��id��class���Ƽ�ʹ��id����class
            singleError: function (e, msg) {
                // �Զ��嵯����ʽ###############
                alert("�����Զ��嵯����ʽ��������Ϣ��" + msg);
            },
            singleSuccess: function (e, msg) {
                // ��֤�����ɹ�֮����ʾ��Ϣ
                alert("���Լ�ͨ����֤�ˣ������Ҳ�֪����");
            },
            endSuccess: function (data) {
                  alert("ȫ����֤�ɹ���������������" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```

##### 3���ڱ���֤֮ǰִ���Զ��庯������Ҫ�Ǳ�дstartCheck����

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--������-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>������֤��data-rule="*"</h3>
        ������   <input type="text" data-rule="*" data-nullmsg="��������Ϊ��" data-errmsg="��֤ʧ��" data-sucmsg="" />

        <br />
        <br />
        <input type="button" id="btn" value="�ύ" />
    </form>
    <script type="text/javascript">

        // �ԣ�����ô�򵥾ͳ�ʼ���ˡ�
        ac.form({
            area: "#frm",   // ��֤����֧�ֱ�ǩ��id��class���Ƽ�ʹ��id����class
            btn: "#btn",     // ������֤�İ�ť����Ԫ�أ�֧�ֱ�ǩ��id��class���Ƽ�ʹ��id����class
            startCheck: function () {
                // �Զ�����֤֮ǰִ�к���
                alert("��ʼ��֤����һ�����ڼ��أ�");
            },
            singleError: function (e, msg) {
                // �Զ��嵯����ʽ###############
                alert("�����Զ��嵯����ʽ��������Ϣ��" + msg);
            },
            singleSuccess: function (e, msg) {
                // ��֤�����ɹ�֮����ʾ��Ϣ
                alert("���Լ�ͨ����֤�ˣ������Ҳ�֪����");
            },
            endSuccess: function (data) {
                  alert("ȫ����֤�ɹ���������������" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```

##### 4���Զ���data-rule��ʶ����������֤�ֻ���̻���data-rule="tm"   ������û�������ʶ��

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--������-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>�ֻ����߹̻���data-rule="tm"  �����Զ�����֤�����ʶ�ģ�����û��tm�ı�ʶ��tm��ʶ�̻������ֻ�</h3>
        �ֻ����߹̻���   <input type="text" data-rule="tm" data-nullmsg="�ֻ���̻�����Ϊ��" data-errmsg="������Ĳ���һ���ֻ����߹̻�" data-sucmsg="" />

        <br />
        <br />
        <input type="button" id="btn" value="�ύ" />
    </form>
    <script type="text/javascript">
        // �Զ����ʶ����
        ac.addRule({
            "tm": /((15)\d{9})|((13)\d{9})|((18)\d{9})|(0[1-9]{2,3}\-?[1-9]{6,7})/i
        });

        // �ԣ�����ô�򵥾ͳ�ʼ���ˡ�
        ac.form({
            area: "#frm",   // ��֤����֧�ֱ�ǩ��id��class���Ƽ�ʹ��id����class
            btn: "#btn",
           endSuccess: function (data) {
                  alert("ȫ����֤�ɹ���������������" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```


#### 3�������������ã�

##### 1�������ж��������������Ƿ�һ������Ҫ�õ�data-sync="ͬ����name����"��ͬ����֤

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--������-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>��֤�������������Ƿ�һ�£�data-rule="s3-10"  ��ע����ͨ��data-sync="��Ҫͬ����֤��nameֵ"����ʱ�����ָ��nameֵ��</h3>
        ����һ��   <input type="password" name="pwd" data-rule="s3-10" data-nullmsg="����������" data-errmsg="����������벻��ȷ" data-sucmsg="" />
        <br />
        <h3>��������data-sync���ԣ����Բ�дdata-rule�ˡ�</h3>
        �������   <input type="password" name="pwd2" data-nullmsg="���ٴ���������" data-errmsg="�������������벻��ȷ" data-sucmsg="" data-sync="pwd" />
        <br />
        <br />
        <input type="button" id="btn" value="�ύ" />
    </form>
    <script type="text/javascript">

        // �ԣ�����ô�򵥾ͳ�ʼ���ˡ�
        ac.form({
            area: "#frm",   // ��֤����֧�ֱ�ǩ��id��class���Ƽ�ʹ��id����class
            btn: "#btn",
            endSuccess: function (data) {
                  alert("ȫ����֤�ɹ���������������" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```

##### 2���������������֤�������д��ִ����֤����Ҫ�õ�data-haved="true"����

```html
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <meta charset="utf-8" />
    <!--������-->
    <script type="text/javascript" src="availdate.js"></script>
</head>
<body>
    <form id="frm">
        <h3>��������3��6���ַ���data-rule="*3-6"����������data-haved="true"֮�󣬾Ͳ�ִ��Ϊ����֤�ˣ�ֻ����дֵ��ʱ���ִ����֤</h3>
        ������   <input type="text" data-rule="*3-6" data-nullmsg="��������Ϊ��" data-errmsg="������3��6���ַ�" data-sucmsg="" data-haved="true" />

        <br />
        <br />
        <input type="button" id="btn" value="�ύ" />
    </form>
    <script type="text/javascript">

        // �ԣ�����ô�򵥾ͳ�ʼ���ˡ�
        ac.form({
            area: "#frm",   // ��֤����֧�ֱ�ǩ��id��class���Ƽ�ʹ��id����class
            btn: "#btn",
            endSuccess: function (data) {
                  alert("ȫ����֤�ɹ���������������" + JSON.stringify(data));
            }
        });

    </script>
</body>
</html>
```

* �����������������֣�����

* availdate.jsΪ[APICloud](http://www.apicloud.com/)�����������������ڴˣ�

* availdate.js��Դ��ַ��[Github](http://git.oschina.net/winu.net/availdate.js)

* QQ����Ⱥ��18863883

* ����֧�֣�[��ɽӮ������Ƽ����޹�˾](http://www.winu.net/)