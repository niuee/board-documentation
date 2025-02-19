[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / ZoomHandlerBoilerPlate

# Class: `abstract` ZoomHandlerBoilerPlate

Defined in: [board-camera/zoom/zoom.ts:21](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L21)

## Extended by

- [`BaseZoomHandler`](BaseZoomHandler.md)
- [`ZoomClampHandler`](ZoomClampHandler.md)
- [`ZoomRestrictionHandler`](ZoomRestrictionHandler.md)
- [`ZoomRig`](ZoomRig.md)

## Implements

- [`ZoomHandler`](../interfaces/ZoomHandler.md)

## Constructors

### new ZoomHandlerBoilerPlate()

> **new ZoomHandlerBoilerPlate**(`nextHandler`): [`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md)

Defined in: [board-camera/zoom/zoom.ts:25](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L25)

#### Parameters

##### nextHandler

[`ZoomHandler`](../interfaces/ZoomHandler.md) = `undefined`

#### Returns

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md)

## Properties

### \_nextHandler?

> `protected` `optional` **\_nextHandler**: [`ZoomHandler`](../interfaces/ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:23](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L23)

## Accessors

### nextHandler

#### Get Signature

> **get** **nextHandler**(): [`ZoomHandler`](../interfaces/ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:33](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L33)

##### Returns

[`ZoomHandler`](../interfaces/ZoomHandler.md)

#### Set Signature

> **set** **nextHandler**(`handler`): `void`

Defined in: [board-camera/zoom/zoom.ts:29](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L29)

##### Parameters

###### handler

[`ZoomHandler`](../interfaces/ZoomHandler.md)

##### Returns

`void`

#### Implementation of

[`ZoomHandler`](../interfaces/ZoomHandler.md).[`nextHandler`](../interfaces/ZoomHandler.md#nexthandler)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`ZoomHandler`](../interfaces/ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:37](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L37)

#### Parameters

##### handler

[`ZoomHandler`](../interfaces/ZoomHandler.md)

#### Returns

[`ZoomHandler`](../interfaces/ZoomHandler.md)

#### Implementation of

[`ZoomHandler`](../interfaces/ZoomHandler.md).[`chainHandler`](../interfaces/ZoomHandler.md#chainhandler)

***

### zoomCameraBy()

> **zoomCameraBy**(`camera`, `delta`): `void`

Defined in: [board-camera/zoom/zoom.ts:48](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L48)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### delta

`number`

#### Returns

`void`

#### Implementation of

[`ZoomHandler`](../interfaces/ZoomHandler.md).[`zoomCameraBy`](../interfaces/ZoomHandler.md#zoomcameraby)

***

### zoomCameraByAt()

> **zoomCameraByAt**(`camera`, `delta`, `at`): `void`

Defined in: [board-camera/zoom/zoom.ts:60](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L60)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### delta

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

[`ZoomHandler`](../interfaces/ZoomHandler.md).[`zoomCameraByAt`](../interfaces/ZoomHandler.md#zoomcamerabyat)

***

### zoomCameraTo()

> **zoomCameraTo**(`camera`, `targetZoom`): `void`

Defined in: [board-camera/zoom/zoom.ts:42](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L42)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### targetZoom

`number`

#### Returns

`void`

#### Implementation of

[`ZoomHandler`](../interfaces/ZoomHandler.md).[`zoomCameraTo`](../interfaces/ZoomHandler.md#zoomcamerato)

***

### zoomCameraToAt()

> **zoomCameraToAt**(`camera`, `to`, `at`): `void`

Defined in: [board-camera/zoom/zoom.ts:54](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L54)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### to

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

[`ZoomHandler`](../interfaces/ZoomHandler.md).[`zoomCameraToAt`](../interfaces/ZoomHandler.md#zoomcameratoat)
