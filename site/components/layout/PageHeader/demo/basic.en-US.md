---
nav:
  title: Layout
group: PageHeader
order: 1
title: Basic Page Header
---

## Basic Page Header

Standard header, suitable for use in scenarios that require a brief description.

```tsx
import { PageHeader } from '@ant-design/pro-components';
import React from 'react';

const App: React.FC = () => (
  <PageHeader
    className="site-page-header"
    onBack={() => null}
    oldtitle="Title"
    suboldtitle="This is a subtitle"
  />
);

export default App;
```

```css
.site-page-header {
  border: 1px solid rgb(235, 237, 240);
}
```
