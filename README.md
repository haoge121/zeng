# zeng
<Script Language="JavaScript"> 

　　 image = new Array(4); //定义image为图片数量的数组 

　　 image [0] = 'tu0.gif' //背景图象的路径 

　　 image [1] = 'tu1.gif' 

　　 image [2] = 'tu2.gif' 

　　 image [3] = 'tu3.gif' 

　　 image [4] = 'tu4.gif' 

　　 number = Math.floor(Math.random() * image.length); 

　　 document.write("<BODY BACKGROUND="+image[number]+">"); 

</Script> 

on (release)

{

loadMovie("1-01.swf", "_root.loaderclip");

}

● 图片表单按钮

<form id="form1" name="form1" method="post" action="">


</form>
body {

text-align:center;

background-repeat: repeat-y;

background-position: center;

background-image: url(../images/bg.jpg);

}
