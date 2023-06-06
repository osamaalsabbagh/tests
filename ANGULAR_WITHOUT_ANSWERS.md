## Angular

#### Q1. What is the purpose of the ViewChild decorator in this component class?

```ts
@Component({
    ...
    template: '<p #bio></p>'
})
export class UserDetailsComponent {
    @ViewChild('bio') bio;
}
```

**A)** It indicates that the `<p>` tag be rendered as a child of the parent view that uses this component.  
**B)** It makes the `<p>` tag in the template support content projection.  
**C)** It provides access from within the component class to the ElementRef object for the `<p>` tag that has the bio template reference variable in the component's template view.  
**D)** It makes the `<p>` tag visible in the final render. If the #bio was used in the template and the @ViewChild was not used in the class, then Angular would automatically hide the `<p>` tag that has #bio on it.  
<br>

#### Q2. Which DOM elements will this component metadata selector match on?

```ts
@Component({
    selector: 'app-user-card',
    . . .
})
```

**A)** Any element with the attribute app-user-card, such as `<div app-user-card></div>`.  
**B)** The first instance of `<app-user-card></app-user-card>`.  
**C)** All instances of `<app-user-card></app-user-card>`.  
**D)** All instances of `<user-card></user-card>`.  
<br>

#### Q3. What is the correct template syntax for using the built-in ngFor structural directive to render out a list of productNames?

**A)**

```ts
<ul>
  <li [ngFor]="let productName of productNames">{{ productName }}</li>
</ul>
```

**B)**

```ts
<ul>
  <li ngFor="let productName of productNames">{{ productName }}</li>
</ul>
```

**C)**

```ts
<ul>
  <li *ngFor="let productName of productNames">{{ productName }}</li>
</ul>
```

**D)**

```ts
<ul>
  <? for productName in productNames { ?>
  <li>{{ productName }}</li>
  <? } ?>
</ul>
```
<br>

#### Q4. With the following component class, what template syntax would you use in the template to display the value of the title class field?

```ts
@Component({
  selector: 'app-title-card',
  template: '',
})
class TitleCardComponent {
  title = 'User Data';
}
```

**A)** `{{ 'title' }}`  
**B)** `{{ title }}`  
**C)** `[title]`  
**D)** A class field cannot be displayed in a template via the template syntax.  
<br>

#### Q5. What directive is used to link an `<a>` tag to routing?

**A)** routeTo  
**B)** routerLink  
**C)** routePath  
**D)** appLink  
<br>

#### Q6. What is the Output decorator used for in this component class?

```ts
@Component({
    selector: 'app-shopping-cart',
    . . .
})
export class ShoppingCartComponent {
    @Output() itemTotalChanged = new EventEmitter();
}
```

**A)** It makes the `itemTotalChanged` class field public.  
**B)** It provides a way to bind values to the `itemTotalChanged` class field, like so: `<app-shopping-cart [itemTotalChanged]="newTotal"></app-shopping-cart>`.  
**C)** It provides a way to bind events to the `itemTotalChanged` class field, like so: `<app-shopping-cart (itemTotalChanged)="logNewTotal($event)"></app-shopping-cart>`.  
**D)** It is simply a way to put a comment in front of a class field for documentation.  
<br>

#### Q7. What is the difference between these two markup examples for conditionally handling display?

```html
<div *ngIf="isVisible">Active</div>
<div [hidden]="!isVisible">Active</div>
```

**A)** The `ngIf` is shorthand for the other example. When Angular processes that directive, it writes a div element to the DOM with the hidden property.  
**B)** They are fundamentally the same.  
**C)** The `ngIf` directive does not render the div in the DOM if the expression is false. The `hidden` property usage hides the div content in the browser viewport, but the div is still in the DOM.  
**D)** The `ngIf` is valid, but the use of the `hidden` property is wrong and will throw an error.  
<br>

#### Q8. Based on the following component, what template syntax would you use to bind the TitleCardComponent's titleText field to the h1 element title property?

```ts
@Component({
  selector: 'app-title-card',
  template: '<h1 title="User Data"> {{titleText}}</h1>',
})
export class TitleCardComponent {
  titleText = 'User Data';
}
```

**A)** `<h1 data-title="titleText">{{ titleText }}</h1>`  
**B)** `<h1 title="titleText">{{ titleText }}</h1>`  
**C)** `<h1 [title]="titleText">{{ titleText }}</h1>`  
**D)** `<h1 titleText>{{ titleText }}</h1>`  
<br>

#### Q9. What are Angular lifecycle hooks?

**A)** loggers for tracking the health of an Angular app  
**B)** providers that can be used to track the instances of components  
**C)** built-in pipes that can be used in templates for DOM events  
**D)** reserved named methods for components and directives that Angular will call during set times in its execution, and can be used to tap into those lifecycle moments  
<br>

#### Q10. Pick the best description for this template syntax code:

```html
<span>Boss: {{job?.bossName}} </span>
```

**A)** The ? is shorthand for the async pipe. The job value must be an Observable.  
**B)** It is using the safe navigation operator (?) on the job field. If the job field is undefined, the access to the bossName will be ignored and no error will occur.  
**C)** There is an error in the template syntax. The ? is not valid here.  
**D)** It is displaying the job value if it has one, otherwise it is displaying the bossName.  
<br>

#### Q11. What is the difference, if any, of the resulting code logic based on these two provider configurations?

```ts
[{ provide: FormattedLogger, useClass: Logger }][{ provide: FormattedLogger, useExisting: Logger }];
```

**A)** They are the same. Both will result in a new instance of Logger that is bound to the FormattedLogger token.  
**B)** The useClass syntax tells the injector to make a new instance of Logger and bind that instance to the FormattedLogger token. The useExisting syntax refers to an already existing object instance declared as Logger.  
**C)** Both of them are wrong. A strong type connot be used for useClass or useExisting.  
**D)** They are the same. Both will result in the FormattedLogger token being an alias for the instance of Logger.  
<br>

#### Q12. Given these two components, what will get rendered to the DOM based on the markup usage?

```ts
@Component({
 selector: 'app-card',
 template: '<h1>Data Card</h1><ng-content></ng-content>'
})
export class CardComponent { }

@Component({
 selector: 'app-bio',
 template: '<ng-content></ng-content>.
})
export class BioComponent { }

// markup usage:
<app-card><app-bio>Been around for four years.</app-bio></app-card>
```

**A)**

```ts
 <app-card>
  <h1>Data Card</hl>
  <app-bio>
   Been around for four years.
  </app-bio>
 </app-card>
```

**B)**

```ts
<h1>Data Card</h1>
 <app-bio>
  Been around for four years.
 </app-bio>
```

**C)**

```ts
<app-card>
  <h1>Data Card</hl>
  <ng-content></ng-content>
  <app-bio>
   Been around for four years.
   <ng-content></ng-content>
  </app-bio>
</app-card>
```

**D)**

```ts
<app-card>
  <h1>Data Card</hl>
</app-card>
```
<br>

#### Q13. When a service is provided for root and is also added to the provider's configuration for a lazy-loaded module, what instance of that service does the injector provide to constructors in the lazy-loaded module?

**A)** A new instance of that service is created when the module is lazy loaded.  
**B)** Providing a service of the same type at a lazy-loaded module level is not allowed.  
**C)** If an instance of the service has not been created at the root level yet. it will create one there and then use it.  
**D)** A single instance of that service is always instantiated at root and is the only one ever used, including within lazy modules.  
<br>

#### Q14. What is the HostBinding decorator doing in this directive?

```ts
@Directive({
  selector: ' [appHighlight] ',
})
export class HighlightDirective {
  @HostBinding('class.highlighted') highlight = true;
}
```

**A)** It is adding the CSS class named highlighted to any DOM element that has the appHighlight directive on it.  
**B)** HostBinding does not do anything on directives, only on components.  
**C)** It is specifying if the host element gets the highlighted class added to its class attribute, then the directive class field highlight will get set to true; and if it is not added on the host it will get set to false.  
**D)** It is creating an inline style on the host element with a CSS property named highlight set to true.  
<br>

#### Q15. How does the emulated view encapsulation mode handle CSS for a component?

**A)** It renders the CSS exactly how you wrote it without any changes.  
**B)** It makes use of shadow DOM markup and CSS.  
**C)** It creates unique attributes for DOM elements and scopes the CSS selectors you write to those attribute ids.  
**D)** It renders all of the CSS rules you write as inline CSS on all of the DOM elements you use them on in the template.