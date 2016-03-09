orientation
=====

基于 JQuery 或者 Zepto.

提供的事件如下: 

   vertical:  手机竖向
   
   -------
   
   手机横屏
   
   hLeft: (←) 手机品牌的logo在左侧
   
   hRight: (→) 手机品牌的logo在右侧
   
   -------

   shake: 摇晃手机

你可以这样去使用:

      $(document).ready(function () {/*must*/
            $(this).vertical(function (event) {
                $("#c").text(event.type);
            });
            $(this).hLeft(function (event) {
                $("#c").text(event.type);
            });
            $(this).hRight(function (event) {
                $("#c").text(event.type);
            });
            $(this).shake(function (event) {
                $("#c").text(event.type);
            });
        });
        
提供一般性的设备方向事件:（如上）

##详细：https://yuminjustin.github.io/?/arc/arcid:02/channel:arc
     
