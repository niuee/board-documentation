[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / ObservableBoardCamera

# Interface: ObservableBoardCamera

Defined in: [board-camera/interface.ts:10](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L10)

## Extends

- [`BoardCamera`](BoardCamera.md)

## Properties

### boundaries?

> `optional` **boundaries**: [`Boundaries`](../type-aliases/Boundaries.md)

Defined in: [board-camera/interface.ts:20](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L20)

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`boundaries`](BoardCamera.md#boundaries)

***

### position

> **position**: [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/interface.ts:15](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L15)

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`position`](BoardCamera.md#position)

***

### rotation

> **rotation**: `number`

Defined in: [board-camera/interface.ts:16](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L16)

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`rotation`](BoardCamera.md#rotation)

***

### rotationBoundaries?

> `optional` **rotationBoundaries**: [`RotationLimits`](../type-aliases/RotationLimits.md)

Defined in: [board-camera/interface.ts:22](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L22)

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`rotationBoundaries`](BoardCamera.md#rotationboundaries)

***

### viewPortHeight

> **viewPortHeight**: `number`

Defined in: [board-camera/interface.ts:19](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L19)

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`viewPortHeight`](BoardCamera.md#viewportheight)

***

### viewPortWidth

> **viewPortWidth**: `number`

Defined in: [board-camera/interface.ts:18](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L18)

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`viewPortWidth`](BoardCamera.md#viewportwidth)

***

### zoomBoundaries?

> `optional` **zoomBoundaries**: [`ZoomLevelLimits`](../type-aliases/ZoomLevelLimits.md)

Defined in: [board-camera/interface.ts:21](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L21)

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`zoomBoundaries`](BoardCamera.md#zoomboundaries)

***

### zoomLevel

> **zoomLevel**: `number`

Defined in: [board-camera/interface.ts:17](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L17)

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`zoomLevel`](BoardCamera.md#zoomlevel)

## Methods

### convertFromViewPort2WorldSpace()

> **convertFromViewPort2WorldSpace**(`point`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/interface.ts:30](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L30)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`convertFromViewPort2WorldSpace`](BoardCamera.md#convertfromviewport2worldspace)

***

### convertFromWorld2ViewPort()

> **convertFromWorld2ViewPort**(`point`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/interface.ts:31](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L31)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`convertFromWorld2ViewPort`](BoardCamera.md#convertfromworld2viewport)

***

### getCameraOriginInWindow()

> **getCameraOriginInWindow**(`centerInWindow`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/interface.ts:29](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L29)

#### Parameters

##### centerInWindow

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`getCameraOriginInWindow`](BoardCamera.md#getcameraorigininwindow)

***

### getTransform()

> **getTransform**(`devicePixelRatio`, `alignCoordinateSystem`): `object`

Defined in: [board-camera/interface.ts:32](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L32)

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

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`getTransform`](BoardCamera.md#gettransform)

***

### on()

> **on**\<`K`\>(`eventName`, `callback`): [`UnSubscribe`](../type-aliases/UnSubscribe.md)

Defined in: [board-camera/interface.ts:11](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L11)

#### Type Parameters

• **K** *extends* keyof [`CameraEventMap`](../type-aliases/CameraEventMap.md)

#### Parameters

##### eventName

`K`

##### callback

(`event`, `cameraState`) => `void`

#### Returns

[`UnSubscribe`](../type-aliases/UnSubscribe.md)

***

### setHorizontalBoundaries()

> **setHorizontalBoundaries**(`min`, `max`): `void`

Defined in: [board-camera/interface.ts:27](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L27)

#### Parameters

##### min

`number`

##### max

`number`

#### Returns

`void`

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`setHorizontalBoundaries`](BoardCamera.md#sethorizontalboundaries)

***

### setMinZoomLevel()

> **setMinZoomLevel**(`minZoomLevel`): `void`

Defined in: [board-camera/interface.ts:26](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L26)

#### Parameters

##### minZoomLevel

`number`

#### Returns

`void`

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`setMinZoomLevel`](BoardCamera.md#setminzoomlevel)

***

### setPosition()

> **setPosition**(`destination`): `boolean`

Defined in: [board-camera/interface.ts:23](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L23)

#### Parameters

##### destination

[`Point`](../type-aliases/Point.md)

#### Returns

`boolean`

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`setPosition`](BoardCamera.md#setposition)

***

### setRotation()

> **setRotation**(`rotation`): `boolean`

Defined in: [board-camera/interface.ts:25](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L25)

#### Parameters

##### rotation

`number`

#### Returns

`boolean`

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`setRotation`](BoardCamera.md#setrotation)

***

### setVerticalBoundaries()

> **setVerticalBoundaries**(`min`, `max`): `void`

Defined in: [board-camera/interface.ts:28](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L28)

#### Parameters

##### min

`number`

##### max

`number`

#### Returns

`void`

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`setVerticalBoundaries`](BoardCamera.md#setverticalboundaries)

***

### setZoomLevel()

> **setZoomLevel**(`zoomLevel`): `boolean`

Defined in: [board-camera/interface.ts:24](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/interface.ts#L24)

#### Parameters

##### zoomLevel

`number`

#### Returns

`boolean`

#### Inherited from

[`BoardCamera`](BoardCamera.md).[`setZoomLevel`](BoardCamera.md#setzoomlevel)
