![hw4_3_1_pageTest_result](https://user-images.githubusercontent.com/70563769/94000547-47560280-fdd2-11ea-99eb-2ca770e5ad4f.jpg)
<!-- pageTest.jsp -->
<%@ page language="java" contentType="text/html; charset=utf-8" pageEncoding="utf-8"%>
<%@ page
		info = "Page Directive Test"
		import = "java.util.*"
		buffer = "10kb"
		autoFlush = "true"
		errorPage = "errorPage.jsp" %>
<!DOCTYPE HTML>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <title>page 지시어 테스트</title>
</head>
<body>
  <h1>
  	  오늘의 날짜는 <%=new Date()%> 입니다. <br/>
  	  이 페이지의 info 속성은 <%=getServletInfo()%> 입니다. <br/>
  </h1>
</body>
</html>
