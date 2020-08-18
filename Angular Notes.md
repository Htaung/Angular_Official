app module is declaration of Module to be used in html
in import [] => add declared module so that angular will be know this module can be used in html


angular build up from component and databinding
directive ngModel => use two way databinding, can build own directive
service & dependency injection 
Routing => for user to look like switching page but it is Single page
Observable => asynchrous code 
Form => user handling, input handling, form handling
Pipes => transfer the output ( what you display on template at runtime)
Http => Web Server =>Angular can't connect to database but can connect to server 
Authenication => 
Optimization =>
Deployment =>
Animation and Test Application


angular.json have defined default css style

property binding =>  property binding [ ]
<a [title]="product.name + ' details'">
Interpolation {{ }} lets you render the property value as text; 
property binding [ ] lets you use the property value in a template expression.

 *ngIf directive so that Angular only creates
 the <p> element if the current product has a description.
 <p *ngIf="product.description">
    Description: {{ product.description }}
  </p>
  
Event binding uses a set of parentheses, ( ), around the event, as in the following <button> element:
<button (click)="share()">
    Share
  </button>
  
  js method code in component.ts
  
  *ngFor
*ngIf
Interpolation {{ }}
Property binding [ ]
Event binding ( )

To know 
ActivatedRoute
FormBuilder
Router
ElementRef
ViewChild
Validators
FormBuilder
FormGroup
Validators
HttpClient
ReactiveFormsModule


The RouterLink directive gives the router control over the anchor element. 
In this case, the route, or URL, contains one fixed segment, /products, 
while the final segment is variable, inserting the id property of the current product. 
For example, the URL for a product with an id of 1 
will be similar to https://getting-started-myfork.stackblitz.io/products/1.

stop at Managing Data
