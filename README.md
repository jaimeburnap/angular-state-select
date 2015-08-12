# angular-state-select

An angular directive that creates list of states in a `<select>` element.

# Usage

Just add it as a dependency to your angular app.

	angular.module('myApp', ['angular-state-select']);

Then inside your template add the attribute to the element that should contain the states.

	<div state-select="state" placeholder=" - select - "></div>

To set a default value set the model to the desired state

	controller('ctrl', ['$scope', function($scope) {
		$scope.state = {state: 'OR'};
	}]);
