# Controllers
## Use controllers to:

Set up the initial state of the $scope object.
Add behavior to the $scope object.

## Do not use controllers to:

Manipulate DOM — Controllers should contain only business logic. Putting any presentation logic into Controllers significantly affects its testability. AngularJS has databinding for most cases and directives to encapsulate manual DOM manipulation.
Format input — Use AngularJS form controls instead.
Filter output — Use AngularJS filters instead.
Share code or state across controllers — Use AngularJS services instead.
Manage the life-cycle of other components (for example, to create service instances).
