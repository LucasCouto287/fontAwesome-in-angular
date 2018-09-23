# fontAwesome-in-angular
*1-install fonts :

  npm i @fortawesome/fontawesome-svg-core
  
  npm i @fortawesome/free-solid-svg-icons
  
  npm i @fortawesome/angular-fontawesome
  
  
*2-import it :
  imports: [
    BrowserModule,
    FontAwesomeModule
  ]


*3-import it to component : 

import { Component } from '@angular/core';

import { faCoffee } from '@fortawesome/free-solid-svg-icons';

*4-export your icon :

export class AppComponent {
  faCoffee = faCoffee;
}

*5-html file :

<div style="text-align:center">
  <fa-icon [icon]="faCoffee"></fa-icon>
</div>
