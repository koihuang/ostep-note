14 内存操作接口 Memory API
===

1.  **内存类型**  
    *   栈内存  
        内存的申请和释放由编译器隐式管理,不需要用户操作.当调用函数时,会在栈上开辟空间存储参数,本地变量,返回值,当函数退出时,释放内存.
    *   堆内存  
        堆内存的申请和释放需要由编程者显示管理(虽然高级语言Java会帮忙完成),栈内存的作用范围都在函数内,存活时间都比较短.堆的内存作用范围比较大,存活时间比较长.
        
2.  **内存申请malloc()调用**  
    malloc的函数定义是: void *malloc(size_t size); malloc通过传入字节数申请内存.返回类型为void是为了方便程序员根据需要转换返回类型,比如转换成double,int等

3.  **内存释放free()调用**  
    free(指针),传入free内存指针,则可以释放改指针占用的堆内存

4.  **常见错误**  
    忘记分配内存,没有分配足够的内存,忘记初始化分配的内存等