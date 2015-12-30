<!DOCTYPE html>
<html>
<script type="text/javascript" src="../../scripts/angular.min.js"></script>
<script type="text/javascript" src="app.js"></script>
<head >
<meta charset="ISO-8859-1">
<title>Quora</title>
</head>
<body ng-app="main">
<div ng-controller="mainCntrl">
<ul>
update name:<input ng-model=text>
<button type="submit">Submit</button>
 <li>{{mainCntrl.temp.firstName[0]}}</li>
 <li>{{mainCntrl.temp.lastName[0]}}</li>
      {{10+10}}
</ul>
</div>

</body>
</html>



(function(){ var app=angular.module('main',[]);
app.controller('mainCntrl',function($scope)
{
	
$scope.temp=employees;
$scope.text="Siya";

	
}



);
})();


var employees=[{
              "firstName":"John", 
               "lastName":"Doe"}];
