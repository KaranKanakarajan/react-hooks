

```cpp
import React from 'react'
import { useState } from 'react';

const App = () => {
  const [num, setnum] = useState(0);
  const [string, setstring] = useState('Karan')
  const [array, setarray] = useState([10,20,30])
  

  function changeNum() {
    setnum(num+1)
    setstring('raj')
    setarray([40,50,60])
  }
  return (
    <>
      <h1>The value of num is {num}</h1>
      <h1>The value of string is {string}</h1>
      <h1>The value of array is {array}</h1>
      <button onClick={changeNum}>Click</button>
    </>

  )
}

export default App



```
---
# Output

![alt text](image.png)


