# CSS Layout

### Ways to position elemnets — positioning schemes: 

- **normal flow**
- **relative positioning**
- **absolute positioning**
- **floats**

### Building Blocks: 

- **block-level**
    - start on a new line
    - block-level elements:
    
```
<h1> , <p> , <ul> , <li> 
```

- **inline box**
    - flow between text
    - inline box elements:
    
```
<img> , <b> , <i>
```

### Box offset properties — to indicate where a box shoud be positioned:

- **fixed positioning**
absolute positioning that positions the element in relation to the browser window  
elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page

- **floating elements**
floating elements take that element out of normal flow and position it to the far left or right of a containing box  
the  floated element becomes a block-level element around which other content can flow

- **z-index**
hen you move any element from normal flow, boxes can overlap  
z-index property allows you to control which box appears on top

### Normal flow:

- `position : static`

### Relative positioning:

- `position : relative`

### Absolute positioning:

- `position : absolute`

### Fixed positioning:

- `position : fixed`
