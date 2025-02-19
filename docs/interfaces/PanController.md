[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / PanController

# Interface: PanController

Defined in: [board-camera/pan/pan.ts:14](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L14)

## Extends

- [`PanHandler`](PanHandler.md)

## Properties

### limitEntireViewPort

> **limitEntireViewPort**: `boolean`

Defined in: [board-camera/pan/pan.ts:15](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L15)

***

### nextHandler?

> `optional` **nextHandler**: [`PanHandler`](PanHandler.md)

Defined in: [board-camera/pan/pan.ts:8](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L8)

#### Inherited from

[`PanHandler`](PanHandler.md).[`nextHandler`](PanHandler.md#nexthandler)

***

### restrictRelativeXTranslation

> **restrictRelativeXTranslation**: `boolean`

Defined in: [board-camera/pan/pan.ts:18](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L18)

***

### restrictRelativeYTranslation

> **restrictRelativeYTranslation**: `boolean`

Defined in: [board-camera/pan/pan.ts:19](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L19)

***

### restrictTranslation

> **restrictTranslation**: `boolean`

Defined in: [board-camera/pan/pan.ts:20](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L20)

***

### restrictXTranslation

> **restrictXTranslation**: `boolean`

Defined in: [board-camera/pan/pan.ts:16](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L16)

***

### restrictYTranslation

> **restrictYTranslation**: `boolean`

Defined in: [board-camera/pan/pan.ts:17](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L17)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`PanHandler`](PanHandler.md)

Defined in: [board-camera/pan/pan.ts:9](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L9)

#### Parameters

##### handler

[`PanHandler`](PanHandler.md)

#### Returns

[`PanHandler`](PanHandler.md)

#### Inherited from

[`PanHandler`](PanHandler.md).[`chainHandler`](PanHandler.md#chainhandler)

***

### panCameraBy()

> **panCameraBy**(`camera`, `delta`): `void`

Defined in: [board-camera/pan/pan.ts:11](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L11)

#### Parameters

##### camera

[`BoardCamera`](BoardCamera.md)

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Inherited from

[`PanHandler`](PanHandler.md).[`panCameraBy`](PanHandler.md#pancameraby)

***

### panCameraTo()

> **panCameraTo**(`camera`, `destination`): `void`

Defined in: [board-camera/pan/pan.ts:10](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L10)

#### Parameters

##### camera

[`BoardCamera`](BoardCamera.md)

##### destination

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Inherited from

[`PanHandler`](PanHandler.md).[`panCameraTo`](PanHandler.md#pancamerato)
