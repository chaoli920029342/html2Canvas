# html2Canvas
进行图片裁剪，兼容移动端和PC端


1.根据dpr，缩放画布，提高裁剪图片的清晰度。

2.根据画布高度设置裁剪高度，避免不可视区域裁剪不到。

3.文件和64位图片的转换
var r= new FileReader();
var f= document.getElementById("uploadImg").files[0];  //uploadImg位input
r.readAsDataURL(f);


var dataUrl = canvas.toDataURL("image/png");
