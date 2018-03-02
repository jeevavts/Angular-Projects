<!DOCTYPE html>
<html>
<head>
	<title>To Do List</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
	<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.4/angular.min.js"></script>
  
</head>
<body ng-app="appToDo" ng-controller="cntrlToDoList" >

<div class="container" style="width:50% !important;padding-top:3%!important;">
	<div class="panel panel-primary">
		<div class="panel-heading">To Do List</div>
		<div class="panel-body">
			<form ng-submit="todoAdd()">
				<div class="form-group">
					<div class="col-sm-10">
					  <input class="form-control" type="text" ng-model="txtInput" size="60" placeholder="Add New">
					</div>
					<input class='btn btn-primary' type="submit" value="Add Task">
				</div>				
			</form>
			<div class="form-group">
					<div class="col-sm-10">
						<div ng-repeat="x in todoList">
							<div class="checkbox">
							  <label><input type="checkbox" ng-model="x.finished"> <span ng-bind="x.listTask"></span></label>
							</div>
						</div>
						<p><button class='btn btn-primary'  ng-click="fnRemove()">Remove marked</button></p>
					</div>
			</div>
</div>
<script>
var app = angular.module('appToDo', []); 
app.controller('cntrlToDoList', function($scope) {
    $scope.todoList = [{listTask:'First Task', finished:false}];

    $scope.todoAdd = function() {
        $scope.todoList.push({listTask:$scope.txtInput, finished:false});
        $scope.txtInput = "";
    };

    $scope.fnRemove = function() {
        var backupList = $scope.todoList;
        $scope.todoList = [];
        angular.forEach(backupList, function(x) {
            if (!x.finished) $scope.todoList.push(x);
        });
    };
});
</script>

</body>
</html>
