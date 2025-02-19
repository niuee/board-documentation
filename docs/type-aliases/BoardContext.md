[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / BoardContext

# Type Alias: BoardContext

> **BoardContext**: `object`

Defined in: [input-state-machine/input-state-machine.ts:33](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/input-state-machine.ts#L33)

## Type declaration

### alignCoordinateSystem

> **alignCoordinateSystem**: `boolean`

### canvas

> **canvas**: [`HTMLCanvasElement`](https://developer.mozilla.org/docs/Web/API/HTMLCanvasElement)

### initialCursorPosition

> **initialCursorPosition**: [`Point`](Point.md)

### notifyOnPan()

> **notifyOnPan**: (`delta`) => `void`

#### Parameters

##### delta

[`Point`](Point.md)

#### Returns

`void`

### notifyOnZoom()

> **notifyOnZoom**: (`zoomAmount`, `anchorPoint`) => `void`

#### Parameters

##### zoomAmount

`number`

##### anchorPoint

[`Point`](Point.md)

#### Returns

`void`

### setInitialCursorPosition()

> **setInitialCursorPosition**: (`position`) => `void`

#### Parameters

##### position

[`Point`](Point.md)

#### Returns

`void`

### setSelectionEndPoint()

> **setSelectionEndPoint**: (`point`) => `void`

#### Parameters

##### point

[`Point`](Point.md)

#### Returns

`void`

### setSelectionStartPoint()

> **setSelectionStartPoint**: (`point`) => `void`

#### Parameters

##### point

[`Point`](Point.md)

#### Returns

`void`

### toggleSelectionBox()

> **toggleSelectionBox**: (`selecting`) => `void`

#### Parameters

##### selecting

`boolean`

#### Returns

`void`
