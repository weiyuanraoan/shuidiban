- MEB 跟桌面(单机) 最大的区别？

  localhost：1234 n 有上限 
  并发请求
  分配给每个用户一个线程 fs 读取一个文件 index
  I/O 吃紧 300左右并发请求 物理 ？ 解决 ？ 多加机器
  物理设变 并联
  ngnix(负载均衡)  那些物理机器空闲 把用户送到这台机器的ip地址  
  钱？
  充分发挥每台机器的性能 ？ 多核 
  1234 => node 进程 => 一个线程  => CPU 
  把CPU都用上
