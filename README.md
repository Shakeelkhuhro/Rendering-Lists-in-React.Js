# Rendering lists in React.JS
Rendering lists in React is a common task when working with dynamic data, such as items from an API or user-generated content.

Create an array of strings called items that represents the list items we want to render. Then use the map method to iterate over the items array and create a new array of React elements, which we then render inside a ul element.

The key prop is used to identify each list item uniquely. It's important to include a key prop when rendering lists in React to help React efficiently update the UI when the list changes. In this case, we're using the item string as the key