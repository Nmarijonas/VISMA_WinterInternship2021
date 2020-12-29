# VISMA_WinterInternship2021
Front-End Developer Task
Create a single-page To-Do application using HTML, JavaScript and CSS without using any
third party libraries.
Requirements:
● Possibility to add a new item
○ Input field for description
■ Required
■ Length up to 160 symbols
○ Input field for deadline
■ Optional
■ Input type is datetime-local (format YYYY-MM-DD HH:MM)
○ ‘Add’ button
■ Adds item to the list
● Use sessionStorage to store the items
■ Clears input fields
● Existing items list
○ Sorting order
■ Least time left to most time left (items without deadline are at the end)
■ Completed items (latest completed is shown on the top)
○ Item in the list should have
■ Description
■ Time left till deadline (show days, hours and minutes)
■ ‘Delete’ button
● Shows confirm popup
● When confirmed removes item from the list completely
● Does nothing if not confirmed
■ Checkbox to mark a completed item
● Marking as completed moves item down the list
● Completed items have line-through style applied to them
