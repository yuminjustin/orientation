orientation
=====

This plugin base on JQuery or Zepto.

It offer generality device orientation events: 
   vertical: Vertical your phone  手机竖向
   
   Horizontal your phone 手机横屏
   hLeft: phone's brand logo at left(←) 手机品牌的logo在左侧
   hRight: phone's brand logo at right(→) 手机品牌的logo在右侧

   shake: Shake your phone 摇晃手机

You can use it like these:

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

contact：

Sina weibo ：http://weibo.com/531205012

Tencent QQ ：1447937286


     
