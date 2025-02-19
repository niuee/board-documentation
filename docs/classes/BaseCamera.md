[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / BaseCamera

# Class: BaseCamera

Defined in: [board-camera/base-camera.ts:10](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L10)

## Implements

- [`BoardCamera`](../interfaces/BoardCamera.md)

## Constructors

### new BaseCamera()

> **new BaseCamera**(`viewPortWidth`, `viewPortHeight`, `position`, `rotation`, `zoomLevel`, `boundaries`, `zoomLevelBoundaries`, `rotationBoundaries`): [`BaseCamera`](BaseCamera.md)

Defined in: [board-camera/base-camera.ts:34](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L34)

#### Parameters

##### viewPortWidth

`number` = `1000`

The width of the viewport. (The width of the canvas in css pixels)

##### viewPortHeight

`number` = `1000`

The height of the viewport. (The height of the canvas in css pixels)

##### position

[`Point`](../type-aliases/Point.md) = `...`

The position of the camera in the world coordinate system

##### rotation

`number` = `0`

The rotation of the camera in the world coordinate system

##### zoomLevel

`number` = `1`

The zoom level of the camera

##### boundaries

[`Boundaries`](../type-aliases/Boundaries.md) = `...`

The boundaries of the camera in the world coordinate system

##### zoomLevelBoundaries

[`ZoomLevelLimits`](../type-aliases/ZoomLevelLimits.md) = `...`

The boundaries of the zoom level of the camera

##### rotationBoundaries

[`RotationLimits`](../type-aliases/RotationLimits.md) = `undefined`

The boundaries of the rotation of the camera

#### Returns

[`BaseCamera`](BaseCamera.md)

## Accessors

### boundaries

#### Get Signature

> **get** **boundaries**(): [`Boundaries`](../type-aliases/Boundaries.md)

Defined in: [board-camera/base-camera.ts:45](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L45)

##### Returns

[`Boundaries`](../type-aliases/Boundaries.md)

#### Set Signature

> **set** **boundaries**(`boundaries`): `void`

Defined in: [board-camera/base-camera.ts:49](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L49)

##### Parameters

###### boundaries

[`Boundaries`](../type-aliases/Boundaries.md)

##### Returns

`void`

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`boundaries`](../interfaces/BoardCamera.md#boundaries)

***

### position

#### Get Signature

> **get** **position**(): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/base-camera.ts:69](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L69)

##### Returns

[`Point`](../type-aliases/Point.md)

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`position`](../interfaces/BoardCamera.md#position)

***

### rotation

#### Get Signature

> **get** **rotation**(): `number`

Defined in: [board-camera/base-camera.ts:141](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L141)

##### Returns

`number`

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`rotation`](../interfaces/BoardCamera.md#rotation)

***

### rotationBoundaries

#### Get Signature

> **get** **rotationBoundaries**(): [`RotationLimits`](../type-aliases/RotationLimits.md)

Defined in: [board-camera/base-camera.ts:145](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L145)

##### Returns

[`RotationLimits`](../type-aliases/RotationLimits.md)

#### Set Signature

> **set** **rotationBoundaries**(`rotationBoundaries`): `void`

Defined in: [board-camera/base-camera.ts:149](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L149)

##### Parameters

###### rotationBoundaries

[`RotationLimits`](../type-aliases/RotationLimits.md)

##### Returns

`void`

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`rotationBoundaries`](../interfaces/BoardCamera.md#rotationboundaries)

***

### viewPortHeight

#### Get Signature

> **get** **viewPortHeight**(): `number`

Defined in: [board-camera/base-camera.ts:61](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L61)

##### Returns

`number`

#### Set Signature

> **set** **viewPortHeight**(`height`): `void`

Defined in: [board-camera/base-camera.ts:65](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L65)

##### Parameters

###### height

`number`

##### Returns

`void`

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`viewPortHeight`](../interfaces/BoardCamera.md#viewportheight)

***

### viewPortWidth

#### Get Signature

> **get** **viewPortWidth**(): `number`

Defined in: [board-camera/base-camera.ts:53](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L53)

##### Returns

`number`

#### Set Signature

> **set** **viewPortWidth**(`width`): `void`

Defined in: [board-camera/base-camera.ts:57](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L57)

##### Parameters

###### width

`number`

##### Returns

`void`

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`viewPortWidth`](../interfaces/BoardCamera.md#viewportwidth)

***

### zoomBoundaries

#### Get Signature

> **get** **zoomBoundaries**(): [`ZoomLevelLimits`](../type-aliases/ZoomLevelLimits.md)

Defined in: [board-camera/base-camera.ts:89](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L89)

##### Returns

[`ZoomLevelLimits`](../type-aliases/ZoomLevelLimits.md)

#### Set Signature

> **set** **zoomBoundaries**(`zoomBoundaries`): `void`

Defined in: [board-camera/base-camera.ts:93](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L93)

##### Parameters

###### zoomBoundaries

[`ZoomLevelLimits`](../type-aliases/ZoomLevelLimits.md)

##### Returns

`void`

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`zoomBoundaries`](../interfaces/BoardCamera.md#zoomboundaries)

***

### zoomLevel

#### Get Signature

> **get** **zoomLevel**(): `number`

Defined in: [board-camera/base-camera.ts:85](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L85)

##### Returns

`number`

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`zoomLevel`](../interfaces/BoardCamera.md#zoomlevel)

## Methods

### convertFromViewPort2WorldSpace()

> **convertFromViewPort2WorldSpace**(`point`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/base-camera.ts:212](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L212)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`convertFromViewPort2WorldSpace`](../interfaces/BoardCamera.md#convertfromviewport2worldspace)

***

### convertFromWorld2ViewPort()

> **convertFromWorld2ViewPort**(`point`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/base-camera.ts:216](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L216)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`convertFromWorld2ViewPort`](../interfaces/BoardCamera.md#convertfromworld2viewport)

***

### getCameraOriginInWindow()

> **getCameraOriginInWindow**(`centerInWindow`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/base-camera.ts:208](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L208)

#### Parameters

##### centerInWindow

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`getCameraOriginInWindow`](../interfaces/BoardCamera.md#getcameraorigininwindow)

***

### getTransform()

> **getTransform**(`devicePixelRatio`, `alignCoorindate`): `object`

Defined in: [board-camera/base-camera.ts:170](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L170)

#### Parameters

##### devicePixelRatio

`number`

The device pixel ratio of the canvas

##### alignCoorindate

`boolean`

Whether to align the coordinate system to the camera's position

#### Returns

`object`

The transformation matrix

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

#### Translation Block

The order of the transformation is as follows:
1. Scale (scale the context using the device pixel ratio)
2. Translation (move the origin of the context to the center of the canvas)
3. Rotation (rotate the context negatively the rotation of the camera)
4. Zoom (scale the context using the zoom level of the camera)
5. Translation (move the origin of the context to the position of the camera in the context coordinate system)

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`getTransform`](../interfaces/BoardCamera.md#gettransform)

***

### invertFromWorldSpace2ViewPort()

> **invertFromWorldSpace2ViewPort**(`point`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/base-camera.ts:220](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L220)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

***

### pointInView()

> **pointInView**(`point`): `boolean`

Defined in: [board-camera/base-camera.ts:258](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L258)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

`boolean`

***

### setHorizontalBoundaries()

> **setHorizontalBoundaries**(`min`, `max`): `void`

Defined in: [board-camera/base-camera.ts:228](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L228)

#### Parameters

##### min

`number`

##### max

`number`

#### Returns

`void`

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`setHorizontalBoundaries`](../interfaces/BoardCamera.md#sethorizontalboundaries)

***

### setMaxZoomLevel()

> **setMaxZoomLevel**(`maxZoomLevel`): `boolean`

Defined in: [board-camera/base-camera.ts:102](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L102)

#### Parameters

##### maxZoomLevel

`number`

#### Returns

`boolean`

***

### setMinZoomLevel()

> **setMinZoomLevel**(`minZoomLevel`): `boolean`

Defined in: [board-camera/base-camera.ts:113](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L113)

#### Parameters

##### minZoomLevel

`number`

#### Returns

`boolean`

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`setMinZoomLevel`](../interfaces/BoardCamera.md#setminzoomlevel)

***

### setPosition()

> **setPosition**(`destination`): `boolean`

Defined in: [board-camera/base-camera.ts:73](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L73)

#### Parameters

##### destination

[`Point`](../type-aliases/Point.md)

#### Returns

`boolean`

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`setPosition`](../interfaces/BoardCamera.md#setposition)

***

### setRotation()

> **setRotation**(`rotation`): `boolean`

Defined in: [board-camera/base-camera.ts:192](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L192)

#### Parameters

##### rotation

`number`

#### Returns

`boolean`

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`setRotation`](../interfaces/BoardCamera.md#setrotation)

***

### setVerticalBoundaries()

> **setVerticalBoundaries**(`min`, `max`): `void`

Defined in: [board-camera/base-camera.ts:245](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L245)

#### Parameters

##### min

`number`

##### max

`number`

#### Returns

`void`

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`setVerticalBoundaries`](../interfaces/BoardCamera.md#setverticalboundaries)

***

### setZoomLevel()

> **setZoomLevel**(`zoomLevel`): `boolean`

Defined in: [board-camera/base-camera.ts:127](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/base-camera.ts#L127)

#### Parameters

##### zoomLevel

`number`

#### Returns

`boolean`

#### Implementation of

[`BoardCamera`](../interfaces/BoardCamera.md).[`setZoomLevel`](../interfaces/BoardCamera.md#setzoomlevel)
