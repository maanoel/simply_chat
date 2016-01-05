angular.module('app.routes', [])

.config(function($stateProvider, $urlRouterProvider) {

  // Ionic uses AngularUI Router which uses the concept of states
  // Learn more here: https://github.com/angular-ui/ui-router
  // Set up the various states which the app can be in.
  // Each state's controller can be found in controllers.js
  $stateProvider
    
      
        
    .state('simplyChat', {
      url: '/login',
      templateUrl: 'templates/simplyChat.html',
      controller: 'simplyChatCtrl'
    })
        
      
    
      
        
    .state('grupos', {
      url: '/chats',
      templateUrl: 'templates/grupos.html',
      controller: 'gruposCtrl'
    })
        
      
    
      
        
    .state('nova_sala', {
      url: '/nova_sala',
      templateUrl: 'templates/nova_sala.html',
      controller: 'nova_salaCtrl'
    })
        
      
    
      
        
    .state('chat_room', {
      url: '/chat_room',
      templateUrl: 'templates/chat_room.html',
      controller: 'chat_roomCtrl'
    })
     
     .state('criandoUmaConta', {
      url: '/novo_usuario',
      templateUrl: 'templates/criandoUmaConta.html',
      controller: 'criandoUmaContaCtrl'
    })   
      
    ;

  // if none of the above states are matched, use this as the fallback
  $urlRouterProvider.otherwise('/login');

});