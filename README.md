# no-fuss-react-snippets

A small collection of simple react snippets that you will actually use.

Support for both JSX and TSX (typescript).

## Snippets

### Import

```javascript
import React from "react";
```

### Functional component

```javascript
export const ComponentName = props => {
    return <></>;
};
```

### Arrow function

```javascript
const FunctionName = args => {};
```

### Use State

```javascript
const [PropName, setPropName] = useState(InitialValue);
```

### Use Effect

```javascript
useEffect(() => {}, []);
```

### Material Icon

For use with [material.io](https://material.io/resources/icons/). Icon name options are provided as a list.

```javascript
<i className="material-icons">settings</i>
```

### Fragment

```javascript
<></>
```

## Typescript snippets

Some snippets have slightly altered snippets when typescript is being used.

### Functional component (TS)

```javascript
interface ComponentNameProps {}

export const ComponentName = (props: ComponentNameProps) => {
    return <></>;
};
```

### Use State (TS)

```javascript
const [PropName, setPropName] = useState<Type>();
```
