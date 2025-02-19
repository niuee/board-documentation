[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / ZoomController

# Interface: ZoomController

Defined in: [board-camera/zoom/zoom.ts:17](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L17)

## Extends

- [`ZoomHandler`](ZoomHandler.md)

## Properties

### nextHandler?

> `optional` **nextHandler**: [`ZoomHandler`](ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:9](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L9)

#### Inherited from

[`ZoomHandler`](ZoomHandler.md).[`nextHandler`](ZoomHandler.md#nexthandler)

***

### restrictZoom

> **restrictZoom**: `boolean`

Defined in: [board-camera/zoom/zoom.ts:18](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L18)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`ZoomHandler`](ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:10](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L10)

#### Parameters

##### handler

[`ZoomHandler`](ZoomHandler.md)

#### Returns

[`ZoomHandler`](ZoomHandler.md)

#### Inherited from

[`ZoomHandler`](ZoomHandler.md).[`chainHandler`](ZoomHandler.md#chainhandler)

***

### zoomCameraBy()

> **zoomCameraBy**(`camera`, `delta`): `void`

Defined in: [board-camera/zoom/zoom.ts:12](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L12)

#### Parameters

##### camera

[`BoardCamera`](BoardCamera.md)

##### delta

`number`

#### Returns

`void`

#### Inherited from

[`ZoomHandler`](ZoomHandler.md).[`zoomCameraBy`](ZoomHandler.md#zoomcameraby)

***

### zoomCameraByAt()

> **zoomCameraByAt**(`camera`, `delta`, `at`): `void`

Defined in: [board-camera/zoom/zoom.ts:14](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L14)

#### Parameters

##### camera

[`BoardCamera`](BoardCamera.md)

##### delta

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Inherited from

[`ZoomHandler`](ZoomHandler.md).[`zoomCameraByAt`](ZoomHandler.md#zoomcamerabyat)

***

### zoomCameraTo()

> **zoomCameraTo**(`camera`, `targetZoom`): `void`

Defined in: [board-camera/zoom/zoom.ts:11](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L11)

#### Parameters

##### camera

[`BoardCamera`](BoardCamera.md)

##### targetZoom

`number`

#### Returns

`void`

#### Inherited from

[`ZoomHandler`](ZoomHandler.md).[`zoomCameraTo`](ZoomHandler.md#zoomcamerato)

***

### zoomCameraToAt()

> **zoomCameraToAt**(`camera`, `to`, `at`): `void`

Defined in: [board-camera/zoom/zoom.ts:13](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L13)

#### Parameters

##### camera

[`BoardCamera`](BoardCamera.md)

##### to

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Inherited from

[`ZoomHandler`](ZoomHandler.md).[`zoomCameraToAt`](ZoomHandler.md#zoomcameratoat)
