# EvaluationStar
        StarView


1、只需要传入frame及图片就好；


2、如果是多行，则在需要添加评价视图的地方修改y值（因为暂时没有解决在多行的情况下直接传递行数的问题）；


3、默认是五颗星，宽高相等；

        1） 默认星星左右之间的距离等于星星的宽度   int imageW = frame.size.width/10;
        2） 点击最右边会全选五颗星，点击最左边仍然会保留一颗星，可以通过下面两种方法
                ①也可以通过把10修改为11，即左边也留点儿手势区域，同样需要对手势点击的位置进行修改；
                ②当然也可以通过滑动手势
        
4、有点击和滑动手势

     
