Title: JSP: If else in JSTL
Tags: jsp,jstl
date: May 5, 2013

And if statement in JSTL is:

	<c:if test="${true}">
		Hiya
	</c>

And if-else is actually choose-when-otherwise:

	<c:choose>
		<c:when test="${true}">
			Hiya
		</c:when>
		<c:otherwise>
			Bye
		</c:otherwise>
	</c:choose>

Don't forget to include the jstl taglib.
