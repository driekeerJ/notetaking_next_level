---
publish: false
<% tp.file.include("[[Base metadata header]]") %>
---
<%* 
	let targetYear = await tp.system.suggester([tp.date.now("YYYY"), tp.date.now("YYYY", +365)], [tp.date.now("YYYY"), tp.date.now("YYYY", +365)])
	await tp.file.move("/Review/" + targetYear + "/OKR-" + targetYear)
-%>
What is an [[OKR|okr]]?

Write at most 5 OKR's every year. What do you want to accomplish.
>[!info]- How to
>1. Create a link for your OKR below
>2. Create the file
>3. Use the template; `Template yearly ORK objective`
>
# Objectives
## Health


## Family


## Work


# Meta
<% tp.file.include("[[Base footer]]") %>