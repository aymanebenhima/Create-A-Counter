# Challenge: Create A Counter Component

## For React.
** If you're familiare with React, head over to your browser and visit: [codesandbox for react](https://react.new)

**Objective:** Build a Counter component that displays a count. The component should have a button to increment the count. Additionally, use useEffect to update the document title with the current count value whenever it changes.

**Requirements:**
1. Use the `useState` hook to manage the count state.
2. Use the `useEffect` hook to update the document title with the current count whenever it changes.
3. Accept an initial count value as a prop and use it to initialize the state.
4. Render the current count and a button to increment the count.

**Starter Code:**
```jsx
import React, { useState, useEffect } from 'react';

function Counter({ initialCount }) {
  // Your code here
}

export default Counter;
```

**Instructions:**
1. Start by initializing the count state using the useState hook and the initialCount prop.
2. Implement the useEffect hook to update the document title with the current count. Remember to include count in the dependency array.
3. Render the count and a button that, when clicked, increments the count.
4. Ensure your component is correctly exported.

---

## For Vue.
** If you're familiare with Vue, head over to your browser and visit: [codesandbox for vue](https://vue.new)

**Objective:** Build a Counter component that displays a count. The component should have a button to increment the count. Additionally, use a Vue.js lifecycle hook to console.log a message every time the component is mounted.

**Requirements:**
1. Use the `ref` function from Vue's Composition API to manage the count state.
2. Use the `onMounted` lifecycle hook from Vue's Composition API to log a message to the console when the component is mounted.
3. Render the current count and a button to increment the count.

**Starter Code:**
```vue
<template>
  <!-- Your code here -->
</template>

<script>
import { ref, onMounted } from 'vue';

export default {
  name: 'Counter',
  setup() {
    // Your code here
  },
};
</script>
```
**Instructions:**
1. Begin by creating a reactive state variable count using the ref function. Initialize it with a value of 0.
2. Implement the increment function that increases the count value by 1 when called.
3. Use the onMounted lifecycle hook to log a message to the console indicating that the component has been mounted.
4. In the template, bind the count to display the current count and create a button that calls the increment function when clicked.
5. Ensure your component is correctly set up to be used in a Vue.js application.

*Good luck!*
