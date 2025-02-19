[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / CameraObservable

# Class: CameraObservable

Defined in: [camera-observer/camera-observer.ts:133](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/camera-observer/camera-observer.ts#L133)

## Constructors

### new CameraObservable()

> **new CameraObservable**(): [`CameraObservable`](CameraObservable.md)

Defined in: [camera-observer/camera-observer.ts:140](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/camera-observer/camera-observer.ts#L140)

#### Returns

[`CameraObservable`](CameraObservable.md)

## Methods

### notifyPan()

> **notifyPan**(`event`, `cameraState`): `void`

Defined in: [camera-observer/camera-observer.ts:147](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/camera-observer/camera-observer.ts#L147)

#### Parameters

##### event

[`CameraPanEventPayload`](../type-aliases/CameraPanEventPayload.md)

##### cameraState

[`CameraState`](../type-aliases/CameraState.md)

#### Returns

`void`

***

### notifyRotate()

> **notifyRotate**(`event`, `cameraState`): `void`

Defined in: [camera-observer/camera-observer.ts:157](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/camera-observer/camera-observer.ts#L157)

#### Parameters

##### event

[`CameraRotateEventPayload`](../type-aliases/CameraRotateEventPayload.md)

##### cameraState

[`CameraState`](../type-aliases/CameraState.md)

#### Returns

`void`

***

### notifyZoom()

> **notifyZoom**(`event`, `cameraState`): `void`

Defined in: [camera-observer/camera-observer.ts:152](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/camera-observer/camera-observer.ts#L152)

#### Parameters

##### event

[`CameraZoomEventPayload`](../type-aliases/CameraZoomEventPayload.md)

##### cameraState

[`CameraState`](../type-aliases/CameraState.md)

#### Returns

`void`

***

### on()

> **on**\<`K`\>(`eventName`, `callback`): [`UnSubscribe`](../type-aliases/UnSubscribe.md)

Defined in: [camera-observer/camera-observer.ts:162](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/camera-observer/camera-observer.ts#L162)

#### Type Parameters

• **K** *extends* keyof [`CameraEventMap`](../type-aliases/CameraEventMap.md)

#### Parameters

##### eventName

`K`

##### callback

(`event`, `cameraState`) => `void`

#### Returns

[`UnSubscribe`](../type-aliases/UnSubscribe.md)
