# Community
This is the community repository for [hiku.dev](https://hiku.dev). Feel free to report an issue or start a discussion.

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

### How Do I get my App featured on Hiku?

Make a post on Twitter, Instagram, Tiktok and Linkedin. Please include a screenshot (or a video) of your app, a short description and the published link. Don't forget to tag our social media account by adding "@hiku_dev #hikudev" to your post. We will promote interesting apps on our social media accounts (See below for the links) and our [app store](https://hiku.app).

Social Media links:
- https://twitter.com/hiku_dev
- https://www.instagram.com/hiku_dev/
- https://www.tiktok.com/@hiku_dev
- https://www.youtube.com/channel/UCYk6ewEXqbx51bUhxHTMnCA
- https://discord.gg/t2FPecjWyH
- https://www.linkedin.com/company/hiku-dev


