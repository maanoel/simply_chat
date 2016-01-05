angular.module('app.controllers', ['ui.router'])
  
.controller('simplyChatCtrl', function($scope, $state) {
	
	$scope.goToPage = function(){
		$state.go('nova_sala');
	}
	
	$scope.newUser = function(){
		$state.go('criandoUmaConta');
	}

})
   
.controller('gruposCtrl', function($scope, $state ) {
	$scope.carregarGrupos = function(){
		$state.go('chat_room');
	}
})
   
.controller('nova_salaCtrl', function($scope, $state) {
	$scope.goToPage = function(){
		$state.go('grupos');
	}
})
   
.controller('chat_roomCtrl', function($scope) {

})
.controller('criandoUmaContaCtrl', function($scope) {
	$scope.enviar = function (usuario) {
	
	}

})
 