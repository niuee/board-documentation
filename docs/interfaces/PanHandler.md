[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / PanHandler

# Interface: PanHandler

Defined in: [board-camera/pan/pan.ts:7](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/pan/pan.ts#L7)

## Extended by

- [`PanController`](PanController.md)

## Properties

### nextHandler?

> `optional` **nextHandler**: [`PanHandler`](PanHandler.md)

Defined in: [board-camera/pan/pan.ts:8](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/pan/pan.ts#L8)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`PanHandler`](PanHandler.md)

Defined in: [board-camera/pan/pan.ts:9](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/pan/pan.ts#L9)

#### Parameters

##### handler

[`PanHandler`](PanHandler.md)

#### Returns

[`PanHandler`](PanHandler.md)

***

### panCameraBy()

> **panCameraBy**(`camera`, `delta`): `void`

Defined in: [board-camera/pan/pan.ts:11](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/pan/pan.ts#L11)

#### Parameters

##### camera

[`BoardCamera`](BoardCamera.md)

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### panCameraTo()

> **panCameraTo**(`camera`, `destination`): `void`

Defined in: [board-camera/pan/pan.ts:10](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/pan/pan.ts#L10)

#### Parameters

##### camera

[`BoardCamera`](BoardCamera.md)

##### destination

[`Point`](../type-aliases/Point.md)

#### Returns

`void`
