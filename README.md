# ngFor\* Directive to render a template for each item in a collection

# Syntax

- src/app.component.ts

```
export class AppComponent {
  public languages = [
    {
      name: 'Angular',
    },
    {
      name: 'Python',
    },
  ];
}
```

- src/app.component.html

```
<ul>
    <li *ngFor="let language of languages">{{ language.name }}</li>
</ul>
```

# Rendered HTML

```
<ul>
    <li>Angular</li>
    <li>Python</li>
</ul>
```
