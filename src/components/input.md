It's a InputField!

```jsx
<InputField />
```

InputField can have 4 different color intents and default to no color.

```jsx
var { Intent } = require("..");

<div className="textAreas">
  <InputField intent={Intent.none} />
  <InputField intent={Intent.primary} />
  <InputField intent={Intent.success} />
  <InputField intent={Intent.warning} />
  <InputField intent={Intent.danger} />
  <style>
    {`
    .textAreas > * {
      margin: 30px 0;
    }

    `}
  </style>
</div>;
```

InputField can fill the width of the parent contaier and can have large font.

```jsx
var { Intent } = require("..");

<div className="textAreas">
  <InputField intent={Intent.primary} fill={true} />
  <InputField intent={Intent.success} large={true} />
  <style>
    {`
    .textAreas > * {
      margin: 30px 0;
    }

    `}
  </style>
</div>;
```
