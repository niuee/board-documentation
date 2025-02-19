[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / ContextCentricCamera

# Class: ContextCentricCamera

Defined in: [board-camera/alt-camera/alt-camera.ts:19](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L19)

## Constructors

### new ContextCentricCamera()

> **new ContextCentricCamera**(`position`, `rotation`, `zoomLevel`, `viewPortWidth`, `viewPortHeight`, `observer`, `boundaries`, `zoomLevelBoundaries`, `rotationBoundaries`): [`ContextCentricCamera`](ContextCentricCamera.md)

Defined in: [board-camera/alt-camera/alt-camera.ts:31](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L31)

#### Parameters

##### position

[`Point`](../type-aliases/Point.md) = `...`

##### rotation

`number` = `0`

##### zoomLevel

`number` = `1`

##### viewPortWidth

`number` = `1000`

##### viewPortHeight

`number` = `1000`

##### observer

[`CameraObserver`](CameraObserver.md) = `...`

##### boundaries

[`Boundaries`](../type-aliases/Boundaries.md) = `...`

##### zoomLevelBoundaries

[`ZoomLevelLimits`](../type-aliases/ZoomLevelLimits.md) = `...`

##### rotationBoundaries

[`RotationLimits`](../type-aliases/RotationLimits.md) = `...`

#### Returns

[`ContextCentricCamera`](ContextCentricCamera.md)

## Accessors

### contextTransform

#### Get Signature

> **get** **contextTransform**(): `object`

Defined in: [board-camera/alt-camera/alt-camera.ts:49](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L49)

##### Returns

`object`

###### position

> **position**: [`Point`](../type-aliases/Point.md)

###### rotation

> **rotation**: `number`

###### zoomLevel

> **zoomLevel**: `number`

***

### observer

#### Get Signature

> **get** **observer**(): [`CameraObserver`](CameraObserver.md)

Defined in: [board-camera/alt-camera/alt-camera.ts:101](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L101)

##### Returns

[`CameraObserver`](CameraObserver.md)

***

### position

#### Get Signature

> **get** **position**(): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/alt-camera/alt-camera.ts:43](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L43)

##### Returns

[`Point`](../type-aliases/Point.md)

***

### rotation

#### Get Signature

> **get** **rotation**(): `number`

Defined in: [board-camera/alt-camera/alt-camera.ts:109](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L109)

##### Returns

`number`

***

### rotationBoundaries

#### Get Signature

> **get** **rotationBoundaries**(): [`RotationLimits`](../type-aliases/RotationLimits.md)

Defined in: [board-camera/alt-camera/alt-camera.ts:143](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L143)

##### Returns

[`RotationLimits`](../type-aliases/RotationLimits.md)

***

### viewportHeight

#### Set Signature

> **set** **viewportHeight**(`height`): `void`

Defined in: [board-camera/alt-camera/alt-camera.ts:135](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L135)

##### Parameters

###### height

`number`

##### Returns

`void`

***

### viewPortHeight

#### Get Signature

> **get** **viewPortHeight**(): `number`

Defined in: [board-camera/alt-camera/alt-camera.ts:127](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L127)

##### Returns

`number`

#### Set Signature

> **set** **viewPortHeight**(`height`): `void`

Defined in: [board-camera/alt-camera/alt-camera.ts:184](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L184)

##### Parameters

###### height

`number`

##### Returns

`void`

***

### viewportWidth

#### Set Signature

> **set** **viewportWidth**(`width`): `void`

Defined in: [board-camera/alt-camera/alt-camera.ts:131](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L131)

##### Parameters

###### width

`number`

##### Returns

`void`

***

### viewPortWidth

#### Get Signature

> **get** **viewPortWidth**(): `number`

Defined in: [board-camera/alt-camera/alt-camera.ts:123](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L123)

##### Returns

`number`

#### Set Signature

> **set** **viewPortWidth**(`width`): `void`

Defined in: [board-camera/alt-camera/alt-camera.ts:180](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L180)

##### Parameters

###### width

`number`

##### Returns

`void`

***

### zoomBoundaries

#### Get Signature

> **get** **zoomBoundaries**(): [`ZoomLevelLimits`](../type-aliases/ZoomLevelLimits.md)

Defined in: [board-camera/alt-camera/alt-camera.ts:139](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L139)

##### Returns

[`ZoomLevelLimits`](../type-aliases/ZoomLevelLimits.md)

***

### zoomLevel

#### Get Signature

> **get** **zoomLevel**(): `number`

Defined in: [board-camera/alt-camera/alt-camera.ts:105](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L105)

##### Returns

`number`

## Methods

### convertFromViewPort2WorldSpace()

> **convertFromViewPort2WorldSpace**(`point`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/alt-camera/alt-camera.ts:80](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L80)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

***

### getCameraOriginInWindow()

> **getCameraOriginInWindow**(`centerInWindow`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/alt-camera/alt-camera.ts:75](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L75)

#### Parameters

##### centerInWindow

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

***

### getTransform()

> **getTransform**(`canvasWidth`, `canvasHeight`, `devicePixelRatio`, `alignCoorindate`): `Transform`

Defined in: [board-camera/alt-camera/alt-camera.ts:113](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L113)

#### Parameters

##### canvasWidth

`number`

##### canvasHeight

`number`

##### devicePixelRatio

`number`

##### alignCoorindate

`boolean`

#### Returns

`Transform`

***

### on()

> **on**\<`K`\>(`eventName`, `callback`): [`UnSubscribe`](../type-aliases/UnSubscribe.md)

Defined in: [board-camera/alt-camera/alt-camera.ts:176](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L176)

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

Defined in: [board-camera/alt-camera/alt-camera.ts:166](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L166)

#### Parameters

##### min

`number`

##### max

`number`

#### Returns

`void`

***

### setMinZoomLevel()

> **setMinZoomLevel**(`minZoomLevel`): `boolean`

Defined in: [board-camera/alt-camera/alt-camera.ts:151](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L151)

#### Parameters

##### minZoomLevel

`number`

#### Returns

`boolean`

***

### setPosition()

> **setPosition**(`destination`): `void`

Defined in: [board-camera/alt-camera/alt-camera.ts:57](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L57)

#### Parameters

##### destination

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### setPositionByDelta()

> **setPositionByDelta**(`delta`): `void`

Defined in: [board-camera/alt-camera/alt-camera.ts:66](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L66)

#### Parameters

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### setPositionWithUserInputDelta()

> **setPositionWithUserInputDelta**(`delta`): `void`

Defined in: [board-camera/alt-camera/alt-camera.ts:71](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L71)

#### Parameters

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### setRotation()

> **setRotation**(`rotation`): `void`

Defined in: [board-camera/alt-camera/alt-camera.ts:93](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L93)

#### Parameters

##### rotation

`number`

#### Returns

`void`

***

### setVerticalBoundaries()

> **setVerticalBoundaries**(`min`, `max`): `void`

Defined in: [board-camera/alt-camera/alt-camera.ts:171](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L171)

#### Parameters

##### min

`number`

##### max

`number`

#### Returns

`void`

***

### setZoomLevel()

> **setZoomLevel**(`zoomLevel`): `void`

Defined in: [board-camera/alt-camera/alt-camera.ts:85](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L85)

#### Parameters

##### zoomLevel

`number`

#### Returns

`void`

***

### viewPortDelta2WorldDelta()

> **viewPortDelta2WorldDelta**(`delta`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/alt-camera/alt-camera.ts:147](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/alt-camera/alt-camera.ts#L147)

#### Parameters

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)
