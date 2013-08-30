package com.onurshome;

import java.io.IOException;
import java.io.PrintWriter;

import javax.servlet.http.*;

@SuppressWarnings("serial")
public class OnurshomeServlet extends HttpServlet {
	public void doGet(HttpServletRequest req, HttpServletResponse resp) throws IOException {
		
		resp.setContentType("text/html");

		PrintWriter out = resp.getWriter();
		out.println("<html>");
		out.println("<head>");
		out.println("<title>Henes Homepage</title>");
		
		out.println("<style>" +
		"#defaultCountdown {" +
		"	width: 250px;" +
 		"}" +
		"</style>");
		
		out.println("<script type=\"text/javascript\" src=\"http://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js\"></script>");
		out.println("<link rel=\"stylesheet\" type=\"text/css\" href=\"javascript/jquery.countdown.css\">"); 
		out.println("<script type=\"text/javascript\" src=\"javascript/jquery.countdown.js\"></script>");
		out.println("<script type=\"text/javascript\">");
		out.println("$(function () {");
		out.println("	$('#defaultCountdown').countdown({until: new Date(2013, 8 - 1, 30), format: 'dHMS'});");
		out.println("});");
		out.println("</script>");
		out.println("</head>");
		
		out.println("<body>");
		out.print("<center><h2>Trainees4Life</h2></center>");
		out.print("<br>");
		out.print("<center><img border='0' src='images/Terminator-Thumbs-Up-as-he-Melts.gif' alt='trainees4life' width='304' height='228'></center>");
		
		out.print("<div style='height: 350px;'></div>");
		out.println("<center><div id='defaultCountdown' width='250px'></div></center>");
		
		out.println("</body>");
		out.println("</html>");
		out.println("");
		out.println("");

	}

	public void doPost(HttpServletRequest req, HttpServletResponse resp) throws IOException {
		doGet(req, resp);
	}
	
}
