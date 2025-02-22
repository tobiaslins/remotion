---
title: <IFrame />
id: iframe
---

The `<IFrame />` can be used like a regular `<iframe>` HTML tag.
The difference is that if you use the component from Remotion, that Remotion will ensure that the iframe is loaded before rendering the frame. That way you can avoid flickers if it happens that the iframe is still loading during rendering.

## Example

```tsx
import {IFrame} from 'remotion';

export const MyComp: React.FC = () => {
  return (
    <IFrame src="https://remotion.dev />
  )
}

```

## See also

- [Use `<Img>` and `<IFrame>` tags](use-img-and-iframe)
