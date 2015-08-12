# angular-state-select
An angular directive that creates list of states in a <select> element

To use just add it as a dependency to your angular app
	angular.module('myApp', ['angular-state-select']);

Then inside your template add the attribute to the element that should contain the states
	<div state-select="state" placeholder=" - select - "></div>