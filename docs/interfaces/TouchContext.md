[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / TouchContext

# Interface: TouchContext

Defined in: [input-state-machine/touch-state-machine.ts:7](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/touch-state-machine.ts#L7)

## Properties

### addTouchPoints()

> **addTouchPoints**: (`points`) => `void`

Defined in: [input-state-machine/touch-state-machine.ts:8](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/touch-state-machine.ts#L8)

#### Parameters

##### points

[`TouchPoints`](../type-aliases/TouchPoints.md)[]

#### Returns

`void`

***

### canvas

> **canvas**: [`HTMLCanvasElement`](https://developer.mozilla.org/docs/Web/API/HTMLCanvasElement)

Defined in: [input-state-machine/touch-state-machine.ts:15](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/touch-state-machine.ts#L15)

***

### getCurrentTouchPointsCount()

> **getCurrentTouchPointsCount**: () => `number`

Defined in: [input-state-machine/touch-state-machine.ts:10](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/touch-state-machine.ts#L10)

#### Returns

`number`

***

### getInitialTouchPointsPositions()

> **getInitialTouchPointsPositions**: (`idents`) => [`TouchPoints`](../type-aliases/TouchPoints.md)[]

Defined in: [input-state-machine/touch-state-machine.ts:11](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/touch-state-machine.ts#L11)

#### Parameters

##### idents

`number`[]

#### Returns

[`TouchPoints`](../type-aliases/TouchPoints.md)[]

***

### notifyOnPan()

> **notifyOnPan**: (`delta`) => `void`

Defined in: [input-state-machine/touch-state-machine.ts:13](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/touch-state-machine.ts#L13)

#### Parameters

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### notifyOnZoom()

> **notifyOnZoom**: (`zoomAmount`, `anchorPoint`) => `void`

Defined in: [input-state-machine/touch-state-machine.ts:14](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/touch-state-machine.ts#L14)

#### Parameters

##### zoomAmount

`number`

##### anchorPoint

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### removeTouchPoints()

> **removeTouchPoints**: (`idents`) => `void`

Defined in: [input-state-machine/touch-state-machine.ts:9](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/touch-state-machine.ts#L9)

#### Parameters

##### idents

`number`[]

#### Returns

`void`

***

### updateTouchPoints()

> **updateTouchPoints**: (`pointsMoved`) => `void`

Defined in: [input-state-machine/touch-state-machine.ts:12](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/touch-state-machine.ts#L12)

#### Parameters

##### pointsMoved

[`TouchPoints`](../type-aliases/TouchPoints.md)[]

#### Returns

`void`
