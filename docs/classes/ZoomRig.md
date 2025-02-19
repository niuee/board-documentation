[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / ZoomRig

# Class: ZoomRig

Defined in: [board-camera/zoom/zoom.ts:186](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/zoom/zoom.ts#L186)

## Extends

- [`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md)

## Implements

- [`ZoomController`](../interfaces/ZoomController.md)

## Constructors

### new ZoomRig()

> **new ZoomRig**(`basePanHandler`, `nextHandler`): [`ZoomRig`](ZoomRig.md)

Defined in: [board-camera/zoom/zoom.ts:192](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/zoom/zoom.ts#L192)

#### Parameters

##### basePanHandler

[`PanHandler`](../interfaces/PanHandler.md)

##### nextHandler

[`ZoomHandler`](../interfaces/ZoomHandler.md) = `undefined`

#### Returns

[`ZoomRig`](ZoomRig.md)

#### Overrides

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`constructor`](ZoomHandlerBoilerPlate.md#constructors)

## Properties

### \_nextHandler?

> `protected` `optional` **\_nextHandler**: [`ZoomHandler`](../interfaces/ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:23](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/zoom/zoom.ts#L23)

#### Inherited from

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`_nextHandler`](ZoomHandlerBoilerPlate.md#_nexthandler)

## Accessors

### nextHandler

#### Get Signature

> **get** **nextHandler**(): [`ZoomHandler`](../interfaces/ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:33](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/zoom/zoom.ts#L33)

##### Returns

[`ZoomHandler`](../interfaces/ZoomHandler.md)

#### Set Signature

> **set** **nextHandler**(`handler`): `void`

Defined in: [board-camera/zoom/zoom.ts:29](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/zoom/zoom.ts#L29)

##### Parameters

###### handler

[`ZoomHandler`](../interfaces/ZoomHandler.md)

##### Returns

`void`

#### Implementation of

[`ZoomController`](../interfaces/ZoomController.md).[`nextHandler`](../interfaces/ZoomController.md#nexthandler)

#### Inherited from

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`nextHandler`](ZoomHandlerBoilerPlate.md#nexthandler-1)

***

### restrictZoom

#### Get Signature

> **get** **restrictZoom**(): `boolean`

Defined in: [board-camera/zoom/zoom.ts:205](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/zoom/zoom.ts#L205)

##### Returns

`boolean`

#### Set Signature

> **set** **restrictZoom**(`restrict`): `void`

Defined in: [board-camera/zoom/zoom.ts:201](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/zoom/zoom.ts#L201)

##### Parameters

###### restrict

`boolean`

##### Returns

`void`

#### Implementation of

[`ZoomController`](../interfaces/ZoomController.md).[`restrictZoom`](../interfaces/ZoomController.md#restrictzoom)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`ZoomHandler`](../interfaces/ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:37](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/zoom/zoom.ts#L37)

#### Parameters

##### handler

[`ZoomHandler`](../interfaces/ZoomHandler.md)

#### Returns

[`ZoomHandler`](../interfaces/ZoomHandler.md)

#### Implementation of

[`ZoomController`](../interfaces/ZoomController.md).[`chainHandler`](../interfaces/ZoomController.md#chainhandler)

#### Inherited from

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`chainHandler`](ZoomHandlerBoilerPlate.md#chainhandler)

***

### zoomCameraBy()

> **zoomCameraBy**(`camera`, `delta`): `void`

Defined in: [board-camera/zoom/zoom.ts:213](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/zoom/zoom.ts#L213)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### delta

`number`

#### Returns

`void`

#### Implementation of

[`ZoomController`](../interfaces/ZoomController.md).[`zoomCameraBy`](../interfaces/ZoomController.md#zoomcameraby)

#### Overrides

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`zoomCameraBy`](ZoomHandlerBoilerPlate.md#zoomcameraby)

***

### zoomCameraByAt()

> **zoomCameraByAt**(`camera`, `delta`, `at`): `void`

Defined in: [board-camera/zoom/zoom.ts:217](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/zoom/zoom.ts#L217)

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

[`ZoomController`](../interfaces/ZoomController.md).[`zoomCameraByAt`](../interfaces/ZoomController.md#zoomcamerabyat)

#### Overrides

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`zoomCameraByAt`](ZoomHandlerBoilerPlate.md#zoomcamerabyat)

***

### zoomCameraTo()

> **zoomCameraTo**(`camera`, `targetZoom`): `void`

Defined in: [board-camera/zoom/zoom.ts:209](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/zoom/zoom.ts#L209)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### targetZoom

`number`

#### Returns

`void`

#### Implementation of

[`ZoomController`](../interfaces/ZoomController.md).[`zoomCameraTo`](../interfaces/ZoomController.md#zoomcamerato)

#### Overrides

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`zoomCameraTo`](ZoomHandlerBoilerPlate.md#zoomcamerato)

***

### zoomCameraToAt()

> **zoomCameraToAt**(`camera`, `to`, `at`): `void`

Defined in: [board-camera/zoom/zoom.ts:221](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/zoom/zoom.ts#L221)

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

[`ZoomController`](../interfaces/ZoomController.md).[`zoomCameraToAt`](../interfaces/ZoomController.md#zoomcameratoat)

#### Overrides

[`ZoomHandlerBoilerPlate`](ZoomHandlerBoilerPlate.md).[`zoomCameraToAt`](ZoomHandlerBoilerPlate.md#zoomcameratoat)
