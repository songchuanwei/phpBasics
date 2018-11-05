&lt;?php



/\*\*

 \* 写出如下程序的输出结果

  &lt;?php

  $data = \['a', 'b', 'c'\];

 foreach\($data as $key =&gt; $val\)

{

      $val = &$data\[$key\];

 }

 \* 程序运行时，每一次循环结束后变量$data的值是什么？请解释

 \* 程序执行完成后，变量$data的值是什么？请解释

 \*/

\['a','b','c'\]

\['b','b','c'\]

\['b','c','c'\]

\['b','c','c'\]

![](/assets/import.png)







