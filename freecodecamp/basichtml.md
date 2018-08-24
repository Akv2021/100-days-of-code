
.########.....###.....######..####..######.....##.....##.########.##.....##.##......
.##.....##...##.##...##....##..##..##....##....##.....##....##....###...###.##......
.##.....##..##...##..##........##..##..........##.....##....##....####.####.##......
.########..##.....##..######...##..##..........#########....##....##.###.##.##......
.##.....##.#########.......##..##..##..........##.....##....##....##.....##.##......
.##.....##.##.....##.##....##..##..##....##....##.....##....##....##.....##.##......
.########..##.....##..######..####..######.....##.....##....##....##.....##.########

1. Make Dead Links Using the Hash Symbol
	Sometimes you want to add a elements to your website before you know where they will link.
	 href="#"

2. Add Placeholder Text to a Text Field
	Placeholder text is what is displayed in your input element before your user has inputted anything.
	<input type="text" placeholder="this is placeholder text">

3. Create a Form Element
	You can build web forms that actually submit data to a server by specifying an action on your form element.
	<form action="/url-where-you-want-to-submit-form-data"></form>

4. Add a Submit Button to a Form
	Clicking submit button will send the data from your form to the URL you specified with your form's action attribute.
	<button type="submit">this button submits the form</button>

5.  Use HTML5 to Require a Field
	if you wanted to make a text input field required, you can just add the attribute required within your input
	 <input type="text" required>

6.  Create a Set of Radio Buttons
	* You can use radio buttons to only give you one answer out of multiple options.
	* Each of your radio buttons can be nested within its own label element. By wrapping an input element inside of a label element it will automatically associate the radio button input with the label element surrounding it.
	* All related radio buttons should have the same name attribute to create a radio button group. 
	* It is considered best practice to set a for attribute on the label element, with a value that matches the value of the id attribute of the input element. This allows assistive technologies to create a linked relationship between the label and the child input element.

		<label for="indoor"> 
		  <input id="indoor" type="radio" name="indoor-outdoor">Indoor 
		</label>

7. Create a Set of Checkboxes
	* use checkboxes for questions that may have more than one answer.
	* Each of your checkboxes can be nested within its own label element. By wrapping an input element inside of a label element it will automatically associate the checkbox input with the label element surrounding it.
	* All related checkbox inputs should have the same name attribute.
	* It is considered best practice to explicitly define the relationship between a checkbox input and its corresponding label by setting the for attribute on the label element to match the id attribute of the associated input element.
	
		<label for="loving">
		<input id="loving" type="checkbox" name="personality"> Loving
		</label>

8. Check Radio Buttons and Checkboxes by Default
	just add the word "checked" to the inside of checkbox or radio button to be checked by default.
		<input type="radio" name="test-name" checked>

9. Declare the Doctype of an HTML Document
	* At the top of your document, you need to tell the browser which version of HTML your page is using. 
		For HTML5, you use <!DOCTYPE html>
	* The ! and uppercase DOCTYPE is important, especially for older browsers. The html is not case sensitive.
	
10. Define the Head and Body of an HTML Document
	*  Any markup with information about your page would go into the head tag.
	*  Then any markup with the content of the page (what displays for a user) would go into the body tag. 
	* Metadata elements, such as link, meta, title, and style, typically go inside the head element.
	* 
	* 
	*	


.########.....###.....######..####..######......######...######...######.
.##.....##...##.##...##....##..##..##....##....##....##.##....##.##....##
.##.....##..##...##..##........##..##..........##.......##.......##......
.########..##.....##..######...##..##..........##........######...######.
.##.....##.#########.......##..##..##..........##.............##.......##
.##.....##.##.....##.##....##..##..##....##....##....##.##....##.##....##
.########..##.....##..######..####..######......######...######...######.






	* 
	* 
	* 
	* 
	* 
