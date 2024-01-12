# Community
This is the community repository for [hony.ai](https://hony.ai). Feel free to report an issue or start a discussion.

## FAQ

### How do I import a segment?
Our editor already supports automatically importing a segment when you start typing the name of one the exports within that segment.
Alternatively, you can import any exported entity from `.` directory:

```typescript
import { App } from '.'
```

### How do I add a new Component?
Use the command Floating Action Button, on the bottom right corner and select the `Create new React Segment` command.


### How Do I install dependencies? Do I need to run `npm install`?
Dependencies are automatically downloaded as soon as you add an import from the package.
Simply import the package as you would on your local machine. Furthermore, if available, the TypeScript typings are also downloaded.

```typescript
import React from 'react'
```


### How do I add CSS?
You can add inline style to react elements or use Emotion for writing CSS-in-JS.

Here's an example:

```tsx
import React from 'react';
import { css } from '@emotion/css'

export const TestComponent = () => {
  return (
    <>
      <div className={css`
      padding: 32px;
      background-color: hotpink;
      font-size: 24px;
      border-radius: 4px;
      &:hover {
        color: red;
      }
    `}>
        {'TestComponent'}
      </div>
    </>
  )
}

```
