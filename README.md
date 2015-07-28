# NiceScroller
�������ƶ���ģ����������

ĿǰNiceScroller�����Ƽ�ȱ�ݣ�

- ����jQuery/Zepto��

ĿǰNiceScroller�߱���������

- ��̬��ȡ��������
- ֧�ֹ��Ի�����
- ֧��Ƕ�ס�

ʹ��NiceScroller�����ƣ�

- ���С��ѹ����(����gzip)�ļ���Сֻ��2.3K��
- ֧���������ƶ��ˡ�

## �÷�

```
<ul id="scroller1">
  <div>content</div>
</ul>
```

```
var scroller = new NiceScroller('#scroller1')
```

-------------------------------------

## ����

`new NiceScroller('#scroller1', config)`

������ | ���� | Ĭ��ֵ | ˵��
---- | ---- | ---- | ----
scrollbar | Boolean | true | �Ƿ���ֹ�����
momentum | Boolean | true | �Ƿ�ʹ�ù��Ի���
animation | String | ease-out | �Զ��嶯��Ч��
x | Number | - | ��ʼX��λ��
y | Number | - | ��ʼY��λ��
onscrollend | Function | - | ���Ի����������ʱ����
ontouchstart | Function | - | �û�����������ʱ����������false����ֹͣ�����¼�����
ontouchend | Function | - | �û���������ʱ����
deceleration | Number | - | ���Ի���������ϵ��

## ����

������ | ���� | ˵��
---- | ---- | ----
scrollTo | x, y, time | timeʱ���ڻ�����x,y��
scrollXTo | x, time | ������ˮƽ������x��
scrollYTo | y, time | ��������ֱ������y��
refresh | cfg | ˢ����������������ò���
destroy | - | ����

## ����

������ | ���� | ˵��
---- | ---- | ----
current | Object | �����鵱ǰ��λ��
point | Object | ��һ�ξ�ֹʱ��λ��
maxScrollWidth | Number | x�᷽�����ɻ���ֵ(��ֵΪ��ֵ)
maxScrollHeight | Number | y�᷽�����ɻ���ֵ(��ֵΪ��ֵ)
jBox | Object | jQuery/Zepto�����ӿ�Ԫ��
jScrollBox | Object | jQuery/Zepto���󣬻���Ԫ��

---------------

### [�鿴DEMO](http://ajccom.github.io/nicescroller/)


