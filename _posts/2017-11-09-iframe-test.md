---
layout: post
title:  "Iframe Test"
date:   2017-11-09 18:01:13
categories: Data_science
permalink: /archivers/2017-11-09-iframe
---
<html > 
<head > 
<script src="js/jquery-1.7.1.js" type="text/javascript"></script> 
<script type="text/javascript"> 
   function GetDivInnerHtml()         
   {          
         $.get("https://developer.ibm.com/kr/developer-%EA%B8%B0%EC%88%A0-%ED%8F%AC%EB%9F%BC/2017/11/08/ibm-cloud-dsx-spark/",function(data){   //OR www.google.com
              $( "#divMain" ).html(data);
         });         
   } 
</script> 
</head> 
<body onload="GetDivInnerHtml()"> 
      <div id="divMain"> </div> 
</body> 
</html>

