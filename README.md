<!-- Import the Struts 2 tag library at the top of your JSP page -->
<%@ taglib prefix="s" uri="/struts-tags" %>

<!-- Use the Struts 2 anchor tag for the first hyperlink with onclick event -->
<s:a href="#" onclick="if (confirm('Are you sure?')) { logoutClick = true; window.location='<s:text name=\"logout.url\"/>'; }">
  <s:div cssClass="HEADERLINK">
    <s:text name="basel. Logout" />
  </s:div>
</s:a>

<!-- Use the Struts 2 anchor tag for the second hyperlink with a static URL -->
<s:a href="Logout.do">
  <s:div cssClass="HEADERLINK">Logout</s:div>
</s:a>
