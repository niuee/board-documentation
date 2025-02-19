[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / BoardCamera

# Interface: BoardCamera

Defined in: [board-camera/interface.ts:14](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L14)

## Extended by

- [`ObservableBoardCamera`](ObservableBoardCamera.md)

## Properties

### boundaries?

> `optional` **boundaries**: [`Boundaries`](../type-aliases/Boundaries.md)

Defined in: [board-camera/interface.ts:20](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L20)

***

### position

> **position**: [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/interface.ts:15](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L15)

***

### rotation

> **rotation**: `number`

Defined in: [board-camera/interface.ts:16](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L16)

***

### rotationBoundaries?

> `optional` **rotationBoundaries**: [`RotationLimits`](../type-aliases/RotationLimits.md)

Defined in: [board-camera/interface.ts:22](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L22)

***

### viewPortHeight

> **viewPortHeight**: `number`

Defined in: [board-camera/interface.ts:19](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L19)

***

### viewPortWidth

> **viewPortWidth**: `number`

Defined in: [board-camera/interface.ts:18](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L18)

***

### zoomBoundaries?

> `optional` **zoomBoundaries**: [`ZoomLevelLimits`](../type-aliases/ZoomLevelLimits.md)

Defined in: [board-camera/interface.ts:21](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L21)

***

### zoomLevel

> **zoomLevel**: `number`

Defined in: [board-camera/interface.ts:17](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L17)

## Methods

### convertFromViewPort2WorldSpace()

> **convertFromViewPort2WorldSpace**(`point`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/interface.ts:30](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L30)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

***

### convertFromWorld2ViewPort()

> **convertFromWorld2ViewPort**(`point`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/interface.ts:31](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L31)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

***

### getCameraOriginInWindow()

> **getCameraOriginInWindow**(`centerInWindow`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/interface.ts:29](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L29)

#### Parameters

##### centerInWindow

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

***

### getTransform()

> **getTransform**(`devicePixelRatio`, `alignCoordinateSystem`): `object`

Defined in: [board-camera/interface.ts:32](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L32)

#### Parameters

##### devicePixelRatio

`number`

##### alignCoordinateSystem

`boolean`

#### Returns

`object`

##### a

> **a**: `number`

##### b

> **b**: `number`

##### c

> **c**: `number`

##### d

> **d**: `number`

##### e

> **e**: `number`

##### f

> **f**: `number`

***

### setHorizontalBoundaries()

> **setHorizontalBoundaries**(`min`, `max`): `void`

Defined in: [board-camera/interface.ts:27](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L27)

#### Parameters

##### min

`number`

##### max

`number`

#### Returns

`void`

***

### setMinZoomLevel()

> **setMinZoomLevel**(`minZoomLevel`): `void`

Defined in: [board-camera/interface.ts:26](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L26)

#### Parameters

##### minZoomLevel

`number`

#### Returns

`void`

***

### setPosition()

> **setPosition**(`destination`): `boolean`

Defined in: [board-camera/interface.ts:23](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L23)

#### Parameters

##### destination

[`Point`](../type-aliases/Point.md)

#### Returns

`boolean`

***

### setRotation()

> **setRotation**(`rotation`): `boolean`

Defined in: [board-camera/interface.ts:25](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L25)

#### Parameters

##### rotation

`number`

#### Returns

`boolean`

***

### setVerticalBoundaries()

> **setVerticalBoundaries**(`min`, `max`): `void`

Defined in: [board-camera/interface.ts:28](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L28)

#### Parameters

##### min

`number`

##### max

`number`

#### Returns

`void`

***

### setZoomLevel()

> **setZoomLevel**(`zoomLevel`): `boolean`

Defined in: [board-camera/interface.ts:24](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/interface.ts#L24)

#### Parameters

##### zoomLevel

`number`

#### Returns

`boolean`
