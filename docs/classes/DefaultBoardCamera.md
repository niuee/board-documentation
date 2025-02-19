[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / DefaultBoardCamera

# Class: DefaultBoardCamera

Defined in: [board-camera/board-camera-v2.ts:12](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L12)

## Implements

- [`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md)

## Constructors

### new DefaultBoardCamera()

> **new DefaultBoardCamera**(`viewPortWidth`, `viewPortHeight`, `position`, `rotation`, `zoomLevel`, `boundaries`, `zoomLevelBoundaries`, `rotationBoundaries`): [`DefaultBoardCamera`](DefaultBoardCamera.md)

Defined in: [board-camera/board-camera-v2.ts:27](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L27)

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

[`DefaultBoardCamera`](DefaultBoardCamera.md)

## Accessors

### boundaries

#### Get Signature

> **get** **boundaries**(): [`Boundaries`](../type-aliases/Boundaries.md)

Defined in: [board-camera/board-camera-v2.ts:32](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L32)

##### Returns

[`Boundaries`](../type-aliases/Boundaries.md)

#### Set Signature

> **set** **boundaries**(`boundaries`): `void`

Defined in: [board-camera/board-camera-v2.ts:36](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L36)

##### Parameters

###### boundaries

[`Boundaries`](../type-aliases/Boundaries.md)

##### Returns

`void`

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`boundaries`](../interfaces/ObservableBoardCamera.md#boundaries)

***

### position

#### Get Signature

> **get** **position**(): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/board-camera-v2.ts:56](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L56)

##### Returns

[`Point`](../type-aliases/Point.md)

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`position`](../interfaces/ObservableBoardCamera.md#position)

***

### rotation

#### Get Signature

> **get** **rotation**(): `number`

Defined in: [board-camera/board-camera-v2.ts:104](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L104)

##### Returns

`number`

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`rotation`](../interfaces/ObservableBoardCamera.md#rotation)

***

### rotationBoundaries

#### Get Signature

> **get** **rotationBoundaries**(): [`RotationLimits`](../type-aliases/RotationLimits.md)

Defined in: [board-camera/board-camera-v2.ts:108](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L108)

##### Returns

[`RotationLimits`](../type-aliases/RotationLimits.md)

#### Set Signature

> **set** **rotationBoundaries**(`rotationBoundaries`): `void`

Defined in: [board-camera/board-camera-v2.ts:112](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L112)

##### Parameters

###### rotationBoundaries

[`RotationLimits`](../type-aliases/RotationLimits.md)

##### Returns

`void`

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`rotationBoundaries`](../interfaces/ObservableBoardCamera.md#rotationboundaries)

***

### viewPortHeight

#### Get Signature

> **get** **viewPortHeight**(): `number`

Defined in: [board-camera/board-camera-v2.ts:48](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L48)

##### Returns

`number`

#### Set Signature

> **set** **viewPortHeight**(`height`): `void`

Defined in: [board-camera/board-camera-v2.ts:52](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L52)

##### Parameters

###### height

`number`

##### Returns

`void`

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`viewPortHeight`](../interfaces/ObservableBoardCamera.md#viewportheight)

***

### viewPortWidth

#### Get Signature

> **get** **viewPortWidth**(): `number`

Defined in: [board-camera/board-camera-v2.ts:40](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L40)

##### Returns

`number`

#### Set Signature

> **set** **viewPortWidth**(`width`): `void`

Defined in: [board-camera/board-camera-v2.ts:44](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L44)

##### Parameters

###### width

`number`

##### Returns

`void`

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`viewPortWidth`](../interfaces/ObservableBoardCamera.md#viewportwidth)

***

### zoomBoundaries

#### Get Signature

> **get** **zoomBoundaries**(): [`ZoomLevelLimits`](../type-aliases/ZoomLevelLimits.md)

Defined in: [board-camera/board-camera-v2.ts:73](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L73)

##### Returns

[`ZoomLevelLimits`](../type-aliases/ZoomLevelLimits.md)

#### Set Signature

> **set** **zoomBoundaries**(`zoomBoundaries`): `void`

Defined in: [board-camera/board-camera-v2.ts:77](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L77)

##### Parameters

###### zoomBoundaries

[`ZoomLevelLimits`](../type-aliases/ZoomLevelLimits.md)

##### Returns

`void`

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`zoomBoundaries`](../interfaces/ObservableBoardCamera.md#zoomboundaries)

***

### zoomLevel

#### Get Signature

> **get** **zoomLevel**(): `number`

Defined in: [board-camera/board-camera-v2.ts:69](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L69)

##### Returns

`number`

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`zoomLevel`](../interfaces/ObservableBoardCamera.md#zoomlevel)

## Methods

### convertFromViewPort2WorldSpace()

> **convertFromViewPort2WorldSpace**(`point`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/board-camera-v2.ts:164](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L164)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`convertFromViewPort2WorldSpace`](../interfaces/ObservableBoardCamera.md#convertfromviewport2worldspace)

***

### convertFromWorld2ViewPort()

> **convertFromWorld2ViewPort**(`point`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/board-camera-v2.ts:168](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L168)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`convertFromWorld2ViewPort`](../interfaces/ObservableBoardCamera.md#convertfromworld2viewport)

***

### getCameraOriginInWindow()

> **getCameraOriginInWindow**(`centerInWindow`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/board-camera-v2.ts:160](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L160)

#### Parameters

##### centerInWindow

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`getCameraOriginInWindow`](../interfaces/ObservableBoardCamera.md#getcameraorigininwindow)

***

### getTransform()

> **getTransform**(`devicePixelRatio`, `alignCoorindate`): `object`

Defined in: [board-camera/board-camera-v2.ts:128](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L128)

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

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`getTransform`](../interfaces/ObservableBoardCamera.md#gettransform)

***

### invertFromWorldSpace2ViewPort()

> **invertFromWorldSpace2ViewPort**(`point`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/board-camera-v2.ts:172](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L172)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

***

### on()

> **on**\<`K`\>(`eventName`, `callback`): [`UnSubscribe`](../type-aliases/UnSubscribe.md)

Defined in: [board-camera/board-camera-v2.ts:210](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L210)

#### Type Parameters

• **K** *extends* keyof [`CameraEventMap`](../type-aliases/CameraEventMap.md)

#### Parameters

##### eventName

`K`

##### callback

(`event`, `cameraState`) => `void`

#### Returns

[`UnSubscribe`](../type-aliases/UnSubscribe.md)

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`on`](../interfaces/ObservableBoardCamera.md#on)

***

### pointInView()

> **pointInView**(`point`): `boolean`

Defined in: [board-camera/board-camera-v2.ts:214](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L214)

#### Parameters

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

`boolean`

***

### setHorizontalBoundaries()

> **setHorizontalBoundaries**(`min`, `max`): `void`

Defined in: [board-camera/board-camera-v2.ts:180](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L180)

#### Parameters

##### min

`number`

##### max

`number`

#### Returns

`void`

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`setHorizontalBoundaries`](../interfaces/ObservableBoardCamera.md#sethorizontalboundaries)

***

### setMaxZoomLevel()

> **setMaxZoomLevel**(`maxZoomLevel`): `boolean`

Defined in: [board-camera/board-camera-v2.ts:81](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L81)

#### Parameters

##### maxZoomLevel

`number`

#### Returns

`boolean`

***

### setMinZoomLevel()

> **setMinZoomLevel**(`minZoomLevel`): `boolean`

Defined in: [board-camera/board-camera-v2.ts:90](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L90)

#### Parameters

##### minZoomLevel

`number`

#### Returns

`boolean`

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`setMinZoomLevel`](../interfaces/ObservableBoardCamera.md#setminzoomlevel)

***

### setPosition()

> **setPosition**(`destination`): `boolean`

Defined in: [board-camera/board-camera-v2.ts:60](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L60)

#### Parameters

##### destination

[`Point`](../type-aliases/Point.md)

#### Returns

`boolean`

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`setPosition`](../interfaces/ObservableBoardCamera.md#setposition)

***

### setRotation()

> **setRotation**(`rotation`): `boolean`

Defined in: [board-camera/board-camera-v2.ts:150](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L150)

#### Parameters

##### rotation

`number`

#### Returns

`boolean`

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`setRotation`](../interfaces/ObservableBoardCamera.md#setrotation)

***

### setVerticalBoundaries()

> **setVerticalBoundaries**(`min`, `max`): `void`

Defined in: [board-camera/board-camera-v2.ts:197](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L197)

#### Parameters

##### min

`number`

##### max

`number`

#### Returns

`void`

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`setVerticalBoundaries`](../interfaces/ObservableBoardCamera.md#setverticalboundaries)

***

### setZoomLevel()

> **setZoomLevel**(`zoomLevel`): `boolean`

Defined in: [board-camera/board-camera-v2.ts:97](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/board-camera-v2.ts#L97)

#### Parameters

##### zoomLevel

`number`

#### Returns

`boolean`

#### Implementation of

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md).[`setZoomLevel`](../interfaces/ObservableBoardCamera.md#setzoomlevel)
