# RegConverter

## 软件介绍
由正则表达式生成最小确定有限自动机

## 使用方法
暂时支持如下正则符号：
    >闭包符   *  
    >连接符   ·（可省略）  
    >或符     |  
    >左右括号 ()  

符号：
>26个小写英文字母

## 测试实验
* Windows 10：
>测试过两台电脑，安装运行成功

* Windows 7：
>机房电脑
>>测试过三台机房电脑，安装运行成功
>教室电脑
>>尝试过7，8台教室电脑，安装成功，运行失败
>>>错误：`无法定位程序输入点 ucrtbase.terminate 于动态链接库 api-ms-win-crt-runtime-|1-1-0.dll 上`
>>>安装Python 3.x安装包后，运行成功
>>>卸载后运行仍然成功（奇怪）

## 安装补丁KB2999226后程序可以成功运行

## 由于时间问题，未能尝试将补丁安装合入安装包
* a
* b
* c
