<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Vue 测试实例 - 菜鸟教程(runoob.com)</title>
    <script src="https://cdn.staticfile.org/vue/2.2.2/vue.min.js"></script>
</head>
<body>
<div id="my">
    <text {{message}}></text>
    </div>
<script>
   new Vue(
       {
           el:"my",
           data:{
               message:"zhongshaohui"
           }
           method:function () {

                for(i=0;i<10;i++)
                {
                    print();
                }


           }
       }
   )

</script>
</body>
</html>

