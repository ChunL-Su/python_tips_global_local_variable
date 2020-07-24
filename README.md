# python_tips_global_local_variable
  - The real rule between global variable and local variable
  - https://blog.csdn.net/warren912/article/details/18988757
  - 在函数中定义的局部变量如果和全局变量同名，则它会隐藏该全局变量。如果想在函数中使用全局变量，则需要使用global进行声明。
  - 以前一直以为是什么就近原则，现在才知道是同名会覆盖全局变量（仅函数内部覆盖，外部调用不影响），所以函数内部只能找到新定义的局部变量
