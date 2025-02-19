[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / BaseZoomHandler

# Class: BaseZoomHandler

Defined in: [board-camera/zoom/zoom.ts:67](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/zoom/zoom.ts#L67)

## Extends

- [`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md)

## Constructors

### new BaseZoomHandler()

> **new BaseZoomHandler**(`panHandler`, `nextHandler`): [`BaseZoomHandler`](BaseZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:71](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/zoom/zoom.ts#L71)

#### Parameters

##### panHandler

[`PanHandler`](../interfaces/PanHandler.md)

##### nextHandler

[`ZoomHandler`](../interfaces/ZoomHandler.md) = `undefined`

#### Returns

[`BaseZoomHandler`](BaseZoomHandler.md)

#### Overrides

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`constructor`](ZoomHandlerBoilerPlate.md#constructors)

## Properties

### \_nextHandler?

> `protected` `optional` **\_nextHandler**: [`ZoomHandler`](../interfaces/ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:23](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/zoom/zoom.ts#L23)

#### Inherited from

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`_nextHandler`](ZoomHandlerBoilerPlate.md#_nexthandler)

## Accessors

### nextHandler

#### Set Signature

> **set** **nextHandler**(`handler`): `void`

Defined in: [board-camera/zoom/zoom.ts:76](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/zoom/zoom.ts#L76)

##### Parameters

###### handler

[`ZoomHandler`](../interfaces/ZoomHandler.md)

##### Returns

`void`

#### Overrides

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`nextHandler`](ZoomHandlerBoilerPlate.md#nexthandler-1)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`ZoomHandler`](../interfaces/ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:37](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/zoom/zoom.ts#L37)

#### Parameters

##### handler

[`ZoomHandler`](../interfaces/ZoomHandler.md)

#### Returns

[`ZoomHandler`](../interfaces/ZoomHandler.md)

#### Inherited from

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`chainHandler`](ZoomHandlerBoilerPlate.md#chainhandler)

***

### zoomCameraBy()

> **zoomCameraBy**(`camera`, `diff`): `void`

Defined in: [board-camera/zoom/zoom.ts:84](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/zoom/zoom.ts#L84)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### diff

`number`

#### Returns

`void`

#### Overrides

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`zoomCameraBy`](ZoomHandlerBoilerPlate.md#zoomcameraby)

***

### zoomCameraByAt()

> **zoomCameraByAt**(`camera`, `delta`, `at`): `void`

Defined in: [board-camera/zoom/zoom.ts:98](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/zoom/zoom.ts#L98)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### delta

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Overrides

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`zoomCameraByAt`](ZoomHandlerBoilerPlate.md#zoomcamerabyat)

***

### zoomCameraTo()

> **zoomCameraTo**(`camera`, `targetZoom`): `void`

Defined in: [board-camera/zoom/zoom.ts:80](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/zoom/zoom.ts#L80)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### targetZoom

`number`

#### Returns

`void`

#### Overrides

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`zoomCameraTo`](ZoomHandlerBoilerPlate.md#zoomcamerato)

***

### zoomCameraToAt()

> **zoomCameraToAt**(`camera`, `to`, `at`): `void`

Defined in: [board-camera/zoom/zoom.ts:90](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/zoom/zoom.ts#L90)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### to

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Overrides

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`zoomCameraToAt`](ZoomHandlerBoilerPlate.md#zoomcameratoat)
