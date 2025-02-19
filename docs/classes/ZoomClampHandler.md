[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / ZoomClampHandler

# Class: ZoomClampHandler

Defined in: [board-camera/zoom/zoom.ts:109](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/zoom/zoom.ts#L109)

## Extends

- [`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md)

## Constructors

### new ZoomClampHandler()

> **new ZoomClampHandler**(`nextHandler`): [`ZoomClampHandler`](ZoomClampHandler.md)

Defined in: [board-camera/zoom/zoom.ts:112](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/zoom/zoom.ts#L112)

#### Parameters

##### nextHandler

[`ZoomHandler`](../interfaces/ZoomHandler.md) = `undefined`

#### Returns

[`ZoomClampHandler`](ZoomClampHandler.md)

#### Overrides

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`constructor`](ZoomHandlerBoilerPlate.md#constructors)

## Properties

### \_nextHandler?

> `protected` `optional` **\_nextHandler**: [`ZoomHandler`](../interfaces/ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:23](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/zoom/zoom.ts#L23)

#### Inherited from

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`_nextHandler`](ZoomHandlerBoilerPlate.md#_nexthandler)

## Accessors

### nextHandler

#### Get Signature

> **get** **nextHandler**(): [`ZoomHandler`](../interfaces/ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:33](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/zoom/zoom.ts#L33)

##### Returns

[`ZoomHandler`](../interfaces/ZoomHandler.md)

#### Set Signature

> **set** **nextHandler**(`handler`): `void`

Defined in: [board-camera/zoom/zoom.ts:29](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/zoom/zoom.ts#L29)

##### Parameters

###### handler

[`ZoomHandler`](../interfaces/ZoomHandler.md)

##### Returns

`void`

#### Inherited from

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`nextHandler`](ZoomHandlerBoilerPlate.md#nexthandler-1)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`ZoomHandler`](../interfaces/ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:37](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/zoom/zoom.ts#L37)

#### Parameters

##### handler

[`ZoomHandler`](../interfaces/ZoomHandler.md)

#### Returns

[`ZoomHandler`](../interfaces/ZoomHandler.md)

#### Inherited from

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`chainHandler`](ZoomHandlerBoilerPlate.md#chainhandler)

***

### zoomByAt()

> **zoomByAt**(`camera`, `delta`, `at`): `void`

Defined in: [board-camera/zoom/zoom.ts:133](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/zoom/zoom.ts#L133)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### delta

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### zoomCameraBy()

> **zoomCameraBy**(`camera`, `diff`): `void`

Defined in: [board-camera/zoom/zoom.ts:121](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/zoom/zoom.ts#L121)

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

Defined in: [board-camera/zoom/zoom.ts:60](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/zoom/zoom.ts#L60)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### delta

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Inherited from

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`zoomCameraByAt`](ZoomHandlerBoilerPlate.md#zoomcamerabyat)

***

### zoomCameraTo()

> **zoomCameraTo**(`camera`, `targetZoom`): `void`

Defined in: [board-camera/zoom/zoom.ts:116](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/zoom/zoom.ts#L116)

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

Defined in: [board-camera/zoom/zoom.ts:128](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/zoom/zoom.ts#L128)

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
