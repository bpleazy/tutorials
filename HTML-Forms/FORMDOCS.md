Element |	Related DOM interface |	Description
--------------|--------------------------|---------------------------------------------
<button> |	HTMLButtonElement	| The button element represents a clickable button.
<datalist> |	HTMLDataListElement	 | The datalist element contains a set of <option> elements that represent the possible options for the value of other form elements.
<fieldset> |	HTMLFieldSetElement	| The fieldset is used to group several form elements within a form.
<form> |	HTMLFormElement	| The form element represents a section of document that contains interactive element that enables a user to submit information to a web server.
<input> |	HTMLInputElement	| The  input element is used to create interactive controls for forms.
<keygen> |	HTMLKeygenElement	| The keygen element exists to facilitate generation of key material, and submission of the public key as part of an HTML form
<label> |	HTMLLabelElement	| The label element represents a caption for an item in a user interface
<legend> |	HTMLLegendElement	| The legend element represents a caption for the content of its parent <fieldset>.
<meter> |	HTMLMeterElement	| The meter element  represents either a scalar value within a known range or a fractional value.
<optgroup> |	HTMLOptGroupElement	| The optgroup element creates a group of options within a <select> element.
<option> |	HTMLOptionElement	| The HTML option element is used to create a control representing an item within a <select>, an <optgroup> or a <datalist> element.
<output> |	HTMLOutputElement	| The output element represents the result of a calculation.
<progress> |	HTMLProgressElement	| The progress element is used to view the completion progress of a task.
<select> |	HTMLSelectElement	| The select element represents a control that presents a menu of options.
<textarea> |	HTMLTextAreaElement	| The textarea element represents a multi-line plain-text editing control.


Attribute Name |	Elements |	Description
---------------|-----------------------|-----------------------------------------------
accept |	<form>, <input>	| List of types the server accepts, typically a file type.
accept-charset |	<form> |	List of supported charsets.
action |	<form> |	The URI of a program that processes the information submitted via the form.
autocomplete |	<form>, <input>	| Indicates whether controls in this form can by default have their values automatically completed by the browser.
autofocus |	<button>, <input>, <keygen>, <select>, <textarea>	| The element should be automatically focused after the page loaded.
challenge	| <keygen>	| A challenge string that is submitted along with the public key.
checked	| <input>	| Indicates whether the element should be checked on page load.
cols	| <textarea>	| Defines the number of columns in a textarea.
data	| <object>	| Specifies the URL of the resource.
dirname |	<input>, <textarea>	 |
disabled |	<button>, <fieldset>, <input>, <keygen>, <optgroup>, <option>, <select>, <textarea>	| Indicates whether the user can interact with the element.
enctype	| <form>	| Defines the content type of the form data when the method is POST.
for |	<label>, <output>	| Describes elements which belong to this one.
form	| <button>, <fieldset>, <input>, <keygen>, <label>, <meter>, <object>, <output>, <progress>, <select>, <textarea>	| Indicates the form that is the owner of the element.
high	| <meter>	| Indicates the lower bound of the upper range.
keytype	| <keygen>	| Specifies the type of key generated.
list	| <input> |	Identifies a list of pre-defined options to suggest to the user.
low	| <meter>	| Indicates the upper bound of the lower range.
max |	<input>, <meter>, <progress> |	Indicates the maximum value allowed.
maxlength	| <input>, <textarea>	| Defines the maximum number of characters allowed in the element.
method	| <form>	| Defines which HTTP method to use when submitting the form. Can be GET (default) or POST.
min	| <input>, <meter> |	Indicates the minimum value allowed.
multiple	| <input>, <select>	| Indicates whether multiple values can be entered in an input of the type email or file.
name	| <button>, <form>, <fieldset>, <input>, <keygen>, <output>, <select>, <textarea>	| Name of the element. For example used by the server to identify the fields in form submits.
novalidate	| <form>	| This attribute indicates that the form shouldn't be validated when submitted.
optimum	| <meter>	 | Indicates the optimal numeric value.
pattern	| <input>	| Defines a regular expression which the element's value will be validated against.
placeholder	| <input>, <textarea>	| Provides a hint to the user of what can be entered in the field.
readonly |	<input>, <textarea>	| Indicates whether the element can be edited or not.
required	| <input>, <select>, <textarea>	| Indicates whether this element is required to fill out or not.
rows |	<textarea>	| Defines the number of rows in a textarea.
selected	| <option>	| Defines a value which will be selected on page load.
size	| <input>, <select>	| Defines the width of the element (in pixels). If the element's type attribute is text or password then it's the number of characters.
src |	<img>	| The URL of the embeddable content.
step	| <input>	 |
target	| <form>	 |
type	| <button>, <input> |	Defines the type of the element.
usemap | 	<img>	 |
value |	<button>, <option>, <input>, <meter>, <progress>	| Defines a default value which will be displayed in the element on page load.
wrap	| <textarea>	| Indicates whether the text should be wrapped or not.
