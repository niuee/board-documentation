[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / CameraObserver

# Class: CameraObserver

Defined in: [camera-observer/camera-observer.ts:56](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/camera-observer/camera-observer.ts#L56)

## Constructors

### new CameraObserver()

> **new CameraObserver**(): [`CameraObserver`](CameraObserver.md)

Defined in: [camera-observer/camera-observer.ts:63](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/camera-observer/camera-observer.ts#L63)

#### Returns

[`CameraObserver`](CameraObserver.md)

## Methods

### clearCallbacks()

> **clearCallbacks**(): `void`

Defined in: [camera-observer/camera-observer.ts:117](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/camera-observer/camera-observer.ts#L117)

#### Returns

`void`

***

### notifyPositionChange()

> **notifyPositionChange**(`delta`, `cameraState`): [`Promise`](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise)\<`void`\>

Defined in: [camera-observer/camera-observer.ts:66](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/camera-observer/camera-observer.ts#L66)

#### Parameters

##### delta

`Point`

##### cameraState

[`CameraState`](../type-aliases/CameraState.md)

#### Returns

[`Promise`](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise)\<`void`\>

***

### notifyRotationChange()

> **notifyRotationChange**(`deltaRotation`, `cameraState`): [`Promise`](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise)\<`void`\>

Defined in: [camera-observer/camera-observer.ts:86](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/camera-observer/camera-observer.ts#L86)

#### Parameters

##### deltaRotation

`number`

##### cameraState

[`CameraState`](../type-aliases/CameraState.md)

#### Returns

[`Promise`](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise)\<`void`\>

***

### notifyZoomChange()

> **notifyZoomChange**(`deltaZoomAmount`, `cameraState`): [`Promise`](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise)\<`void`\>

Defined in: [camera-observer/camera-observer.ts:76](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/camera-observer/camera-observer.ts#L76)

#### Parameters

##### deltaZoomAmount

`number`

##### cameraState

[`CameraState`](../type-aliases/CameraState.md)

#### Returns

[`Promise`](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise)\<`void`\>

***

### on()

> **on**\<`K`\>(`eventName`, `callback`): [`UnSubscribe`](../type-aliases/UnSubscribe.md)

Defined in: [camera-observer/camera-observer.ts:96](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/camera-observer/camera-observer.ts#L96)

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

### onAllUpdate()

> **onAllUpdate**(`callback`): [`UnSubscribe`](../type-aliases/UnSubscribe.md)

Defined in: [camera-observer/camera-observer.ts:112](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/camera-observer/camera-observer.ts#L112)

#### Parameters

##### callback

[`ConslidateCallback`](../type-aliases/ConslidateCallback.md)

#### Returns

[`UnSubscribe`](../type-aliases/UnSubscribe.md)
