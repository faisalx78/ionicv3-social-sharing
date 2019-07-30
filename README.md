
```
ionic cordova plugin add cordova-plugin-x-socialsharing
npm install --save @ionic-native/social-sharing@4.20.0
```
#### app.module.ts
```
import { SocialSharing } from '@ionic-native/social-sharing';


...


providers: [
    SocialSharing,
  ]
```
#### home.ts
```
import { SocialSharing } from '@ionic-native/social-sharing';


....



export class HomePage {

  message: string = 'title';
  file: string = '';
  subject: string = '';
  link: string = 'http://google.com';
```
#### home.html
```
<button ion-button (click)="share()"></button
```
