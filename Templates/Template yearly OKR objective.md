---
<%* 
	const title = await tp.file.folder(true).split("/")[1]
	const targetYear = await tp.file.folder(true).split("/")[1]
	await tp.file.move("/Review/" + targetYear + "/Objectives/" + tp.file.title)
-%>
publish: false
<% tp.file.include("[[Base metadata header]]") %>
---
## Key Results
>[!info]- What are key results?
A Key Result is a measurable outcome required to achieve the Objective. It contains a metric with a start and target value. Key Results measure progress towards the Objective — like a signpost that shows how close you are to your Objective.
- 

## Related core values
>[!info]- What value is this relating to
>See [[Core principles|my core principles]]
- 

## Initiatives to make this happen
>[!info]- Wat are the initiatives?
>Initiatives are all the projects and tasks that will help you achieve a Key Result. Imagine your organization is a car. The Objective is your destination, the Key Results show if you’re heading in the right direction, and the Initiatives are what you’ll do to get your car moving.
- 

<% tp.file.include("[[Base footer]]") %>