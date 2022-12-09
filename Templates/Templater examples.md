# *Single line templater example*
Date: <%tp.date.now("YYYY-MM-DD")%>. See [Moment JS](https://momentjs.com/)
tldr: <% tp.system.prompt("TLDR")%>
type: <%tp.system.suggester(["technical", "cooking", "tips"], ["a", "b", "c"])%>

# *Multiline javascript codeblock*
<%* 
	function log(msg) { 
		console.log(msg); 
	} 
	let author = "Jeroen van der Wal"
%> 

<%* 
	log("Title: " + tp.file.title) 
	log("Author: " + author) 
%>
