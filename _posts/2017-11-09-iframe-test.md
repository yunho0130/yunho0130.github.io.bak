---
layout: post
title:  "Iframe Test"
date:   2017-11-09 18:01:13
categories: Data_science
permalink: /archivers/2017-11-09-iframe
---
add hello alert
<html > 
<head > 
<script src="https://yunho0130.github.io/js/jquery-3.2.1.js" type="text/javascript"></script> 
<script type="text/javascript"> 
   function GetDivInnerHtml()         
   {          
         $.get("https://developer.ibm.com/kr/developer-%EA%B8%B0%EC%88%A0-%ED%8F%AC%EB%9F%BC/2017/11/08/ibm-cloud-dsx-spark/",function(data){   //OR www.google.com
              $( "#divMain" ).html(data);
         });         
   } 

$(document).ready(function(){

   start(); // 문서가 준비되면 start 함수를 실행한다.

   function start(){
      setTimeout(start,1000); // 1초 후 start를 재귀호출한다.
      console.log('hello~'); // 크롬 브라우저라면 F12를 눌러 확인할 수 있다.
      alert('hello~');
   }
});

</script> 
</head> 
<body onload="GetDivInnerHtml()"> 
      <div id="divMain"> </div> 
</body> 
</html>

