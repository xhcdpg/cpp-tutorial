# 名字空间

## 为什么需要名字空间

* 划分逻辑单元
* 避免名字冲突

## 什么是名字空间

* 名字空间定义
* 名字空间合并
* 声明定义分开

## 怎样用名字空间

* 作用域限定符
* 名字空间指令
* 名字空间声明

## 无名名字空间

* 不属于任何有名名字空间的标识符，隶属于无名命名空间
* 无名命名空间的成员，直接通过`::`访问

## 名字空间嵌套与名字空间别名

* 内层标识符隐藏外层同名标识符
* 嵌套的名字空间需要逐层分解
* 可通过名字空间别名简化书写
    * `namespace ns_four = ns1::ns2::ns3::ns4;`