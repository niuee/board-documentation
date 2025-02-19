[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / BoardStateObserver

# Class: BoardStateObserver

Defined in: [boardify/board-state-observer.ts:21](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L21)

## Constructors

### new BoardStateObserver()

> **new BoardStateObserver**(`camera`): [`BoardStateObserver`](BoardStateObserver.md)

Defined in: [boardify/board-state-observer.ts:33](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L33)

#### Parameters

##### camera

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md)

#### Returns

[`BoardStateObserver`](BoardStateObserver.md)

## Accessors

### camera

#### Get Signature

> **get** **camera**(): [`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md)

Defined in: [boardify/board-state-observer.ts:68](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L68)

##### Returns

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md)

#### Set Signature

> **set** **camera**(`camera`): `void`

Defined in: [boardify/board-state-observer.ts:72](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L72)

##### Parameters

###### camera

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md)

##### Returns

`void`

***

### panHandler

#### Get Signature

> **get** **panHandler**(): [`PanController`](../interfaces/PanController.md)

Defined in: [boardify/board-state-observer.ts:77](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L77)

##### Returns

[`PanController`](../interfaces/PanController.md)

#### Set Signature

> **set** **panHandler**(`panHandler`): `void`

Defined in: [boardify/board-state-observer.ts:81](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L81)

##### Parameters

###### panHandler

[`PanController`](../interfaces/PanController.md)

##### Returns

`void`

***

### rotationHandler

#### Get Signature

> **get** **rotationHandler**(): [`RotationHandler`](../interfaces/RotationHandler.md)

Defined in: [boardify/board-state-observer.ts:95](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L95)

##### Returns

[`RotationHandler`](../interfaces/RotationHandler.md)

#### Set Signature

> **set** **rotationHandler**(`rotationHandler`): `void`

Defined in: [boardify/board-state-observer.ts:99](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L99)

##### Parameters

###### rotationHandler

[`RotationHandler`](../interfaces/RotationHandler.md)

##### Returns

`void`

***

### zoomHandler

#### Get Signature

> **get** **zoomHandler**(): [`ZoomController`](../interfaces/ZoomController.md)

Defined in: [boardify/board-state-observer.ts:86](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L86)

##### Returns

[`ZoomController`](../interfaces/ZoomController.md)

#### Set Signature

> **set** **zoomHandler**(`zoomHandler`): `void`

Defined in: [boardify/board-state-observer.ts:90](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L90)

##### Parameters

###### zoomHandler

[`ZoomController`](../interfaces/ZoomController.md)

##### Returns

`void`

## Methods

### notifyCameraChange()

> **notifyCameraChange**(): `void`

Defined in: [boardify/board-state-observer.ts:104](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L104)

#### Returns

`void`

***

### notifyPanHandlerChange()

> **notifyPanHandlerChange**(): `void`

Defined in: [boardify/board-state-observer.ts:108](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L108)

#### Returns

`void`

***

### notifyRotationHandlerChange()

> **notifyRotationHandlerChange**(): `void`

Defined in: [boardify/board-state-observer.ts:116](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L116)

#### Returns

`void`

***

### notifyZoomHandlerChange()

> **notifyZoomHandlerChange**(): `void`

Defined in: [boardify/board-state-observer.ts:112](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L112)

#### Returns

`void`

***

### subscribeToCamera()

> **subscribeToCamera**(`subscriber`): `void`

Defined in: [boardify/board-state-observer.ts:37](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L37)

#### Parameters

##### subscriber

[`BoardCameraSubscriber`](../interfaces/BoardCameraSubscriber.md)

#### Returns

`void`

***

### subscribeToPanHandler()

> **subscribeToPanHandler**(`subscriber`): `void`

Defined in: [boardify/board-state-observer.ts:45](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L45)

#### Parameters

##### subscriber

[`BoardPanHandlerSubscriber`](../interfaces/BoardPanHandlerSubscriber.md)

#### Returns

`void`

***

### subscribeToRotationHandler()

> **subscribeToRotationHandler**(`subscriber`): () => `void`

Defined in: [boardify/board-state-observer.ts:61](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L61)

#### Parameters

##### subscriber

[`BoardRotationHandlerSubscriber`](../interfaces/BoardRotationHandlerSubscriber.md)

#### Returns

`Function`

##### Returns

`void`

***

### subscribeToZoomHandler()

> **subscribeToZoomHandler**(`subscriber`): `void`

Defined in: [boardify/board-state-observer.ts:53](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L53)

#### Parameters

##### subscriber

[`BoardZoomHandlerSubscriber`](../interfaces/BoardZoomHandlerSubscriber.md)

#### Returns

`void`

***

### unsubscribeToCamera()

> **unsubscribeToCamera**(`subscriber`): `void`

Defined in: [boardify/board-state-observer.ts:41](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L41)

#### Parameters

##### subscriber

[`BoardCameraSubscriber`](../interfaces/BoardCameraSubscriber.md)

#### Returns

`void`

***

### unsubscribeToPanHandler()

> **unsubscribeToPanHandler**(`subscriber`): `void`

Defined in: [boardify/board-state-observer.ts:49](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L49)

#### Parameters

##### subscriber

[`BoardPanHandlerSubscriber`](../interfaces/BoardPanHandlerSubscriber.md)

#### Returns

`void`

***

### unsubscribeToZoomHandler()

> **unsubscribeToZoomHandler**(`subscriber`): `void`

Defined in: [boardify/board-state-observer.ts:57](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/boardify/board-state-observer.ts#L57)

#### Parameters

##### subscriber

[`BoardZoomHandlerSubscriber`](../interfaces/BoardZoomHandlerSubscriber.md)

#### Returns

`void`
