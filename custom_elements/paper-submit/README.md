paper-submit
===

This is a little Polymer web component which enables to use `paper-button`s like submit buttons for the `form`s. This is achieved by injecting a `button` as first, hidden element of the closest `form` element and clicking on it.

---

How to use
===
Simply put the `paper-submit` element inside a form. It will act like a normal `paper-button`, plus it will submit the `form`. Extra attribute: `bClass`, used to set the innser `paper-button`'s class.

Example

	<form method="post">
		<input type="text" name="username" placeholder="Username" />
		<input type="password" name="password" placeholder="Password" />
		<paper-submit bClass="blue">Send</paper-submit>
	</form>