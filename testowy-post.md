---
id: testowy-post
title: Testowy post
introduction: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
date: 2022-01-11 12:00:00
image: images/testowy-post/img.png
categories:
- Test
authors:
- AdiPol1359
---

## Testowy post

### Lorem ipsum
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

```js
import { useState } from 'react';

const FooComponent = () => {
  const [visible, setVisible] = useState(true);

  const handleButtonClick = () => setVisible((prev) => !prev);

  return (
    <>
      {visible && <div>This element is visible!</div>}

      <button onClick={handleButtonClick}>
        {visible ? "Hide element" : "Show element"}
      </button>
    </>
  );
};

export default FooComponent;
```

![img](images/testowy-post/img.png)
