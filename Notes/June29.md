## June 29th
- Themes in Material UI
- stopPropogation
- useState(''); 
- const [fullName, setFullName] = useState('');

### States
- Component re-rendering you cant just have a variable
- B/c components re-render it clears out code
- React outsources where it stores data
- Actual data is stored in React (React RAM) -> stored outside the component
    - Every time it re-renders we needta go check it -> gets stored in react ram
- Pointer
- Components auto re-render every time state changes
- Conditional rendering

- Look into how to break things down into components

## Tic Tac Toe
- Once clicked fires a function ->
- Click means change to x
- React usually re-renders components
- 

## Multiple pages
- document.js


## Adding a container
- import Container from '@mui/material/Container'


- Variant and id are important

```
import Text

export default function TodoList(){
    return(
        <TextField
        id="standard-basic"
        >
    )
}
```

### Organize by types of components as well

//MUI components
//own components