[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / ZoomHandler

# Interface: ZoomHandler

Defined in: [board-camera/zoom/zoom.ts:8](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L8)

## Extended by

- [`ZoomController`](ZoomController.md)

## Properties

### nextHandler?

> `optional` **nextHandler**: [`ZoomHandler`](ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:9](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L9)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`ZoomHandler`](ZoomHandler.md)

Defined in: [board-camera/zoom/zoom.ts:10](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/zoom/zoom.ts#L10)

#### Parameters

##### handler

[`ZoomHandler`](ZoomHandler.md)

#### Returns

[`ZoomHandler`](ZoomHandler.md)

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
