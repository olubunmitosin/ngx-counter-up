# ngx-counter-up
 == Angular 7

# Installation
* Install NPM ngx counter up
```bash
npm install ngx-counter-up --save
```

* Add CounterUpModule to your app.module.ts
```javascript
import { CounterUpModule } from 'ngx-counter-up';
@NgModule({
  imports: [ CounterUpModule.forRoot() ]
})
```

## Usage
* You can use counter-up component like so：
```html
<span counter-up offset="1" number="1000">0</span>
```

```javascript
import { CounterUpModule } from 'ngx-counter-up';
@NgModule({
  imports: [ CounterUpModule.forRoot({
    delay: 1000,
    time: 100
  }) ]
})
```

## Callbacks( Output )
* You can apply complete callback function：
```html
<span counter-up number="10" (complete)="log($event)">9</span>
```

## Feedback

Please [leave your feedback](https://github.com/yiller/ng4-icheck/issues) if you have noticed any issues or have a feature request.

## License

The repository code is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
