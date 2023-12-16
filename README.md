# HTML5-date-input

<input>
Many forms need to gather information such as dates, email addresses, and URLs. This has traditionally been done using text inputs.HTML5 introduces new form controls to standardize the way that some information is gathered. Older browsers that do not recognize these inputs will just treat them as a single line text box. 
type="date"
If you are asking the user for a date, you can use an <input>element and give the typeattribute a value of date. This will create a date input in browsers that support the new 
HMTL5 input types. 

<form action="http://www.example.com/bookings/" 
 method="post">
<label for="username">Departure date:</label>
<input type="date" name="depart" />
<input type="submit" value="Submit" />
</form>

