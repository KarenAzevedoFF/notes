# React Draggable

Library: https://github.com/mzabriskie/react-draggable

## Pros

Decent examples

Decent tutorial

Good documentation

Flexible

There are 2 Draggable Component types. The Draggable that manages its own state and the Draggable Core Component. It has no internal state. This is useful as an abstraction over touch and mouse events but with full control

It's super customizable.

I believe that It will save us a lot of work

## Cons

I did not find any


## Using

The <Draggable/> component transparently adds draggability to its children.

_Note:_ Only a single child is allowed or an Error will be thrown.

**style** is used to give the transform css to the child.

**className** is used to apply the proper classes to the object being dragged.

**onMouseDown, onMouseUp, onTouchStart, and onTouchEnd** are used to keep track of dragging state.

**Props**:

`allowAnyClick`: boolean,

`axis`: string, - Determines which axis the draggable can move

`bounds`: {left: number, top: number, right: number, bottom: number} | string, - Specifies movement boundaries

`cancel`: string, - Specifies a selector to be used to prevent drag initialization

`defaultClassName`: string,

`defaultClassNameDragging`: string,

`defaultClassNameDragged`: string,

`defaultPosition`: {x: number, y: number}, Specifies the `x` and `y` that the dragged item should start at. This is generally not necessary to use (you can use absolute or relative)

`disabled`: boolean,

`grid`: [number, number], - Specifies the x and y that dragging should snap to.

`handle`: string, - Specifies a selector to be used as the handle that initiates drag.

`offsetParent`: HTMLElement,

`onMouseDown`: (e: MouseEvent) => void,

`onStart`: DraggableEventHandler - Called when dragging starts

`onDrag`: DraggableEventHandler - Called while dragging.

`onStop`: DraggableEventHandler - Called when dragging stops

`position`: {x: number, y: number} - if you need to have direct control of the element.

`positionOffset`: {x: number | string, y: number | string}, - A position offset to start with. Useful for giving an initial position

`scale`: number
