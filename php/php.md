# php

## 一、基础

1. 语法基础
   + 值传递
   + 赋值引用
   + copy on write
2. 常见函数使用
   + array_chunk
   + array_column
   + array_merge
   + array_count_values
   + array_diff(差集), array_intersect
   + array_fill_keys
   + array_fill
   + array_filter
   + array_flip
   + array_intersect
   + array_keys
   + array_map
   + array_merge & +
   + array_multisort
   + array_pop(出栈), array_push(arr[] = a)
   + array_rand($arr, $num)  随机返回的是key，不是value
   + mt_rand($a, $b)，生成的$r<=b, $r>=$a
   + shuffle(&$arr)
   + array_shift(&$arr), array_unshift(&$arr)
   + array_slice(获取子字符串), array_splice(替换其中的某个子串)。注意length参数为负数时。
   + 
3. 面向对象



## 二、php-fpm

1. 运行模式 socket fast-cgi
2. php-fpm配置优化
