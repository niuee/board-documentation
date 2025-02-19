[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / PanHandlerBoilerPlate

# Class: `abstract` PanHandlerBoilerPlate

Defined in: [board-camera/pan/pan.ts:23](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/pan/pan.ts#L23)

## Extended by

- [`BasePanHandler`](BasePanHandler.md)
- [`ClampHandler`](ClampHandler.md)
- [`PanWithRestriction`](PanWithRestriction.md)
- [`PanRig`](PanRig.md)

## Implements

- [`PanHandler`](../interfaces/PanHandler.md)

## Constructors

### new PanHandlerBoilerPlate()

> **new PanHandlerBoilerPlate**(`nextHandler`): [`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md)

Defined in: [board-camera/pan/pan.ts:27](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/pan/pan.ts#L27)

#### Parameters

##### nextHandler

[`PanHandler`](../interfaces/PanHandler.md) = `undefined`

#### Returns

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md)

## Properties

### \_nextHandler?

> `protected` `optional` **\_nextHandler**: [`PanHandler`](../interfaces/PanHandler.md)

Defined in: [board-camera/pan/pan.ts:25](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/pan/pan.ts#L25)

## Accessors

### nextHandler

#### Get Signature

> **get** **nextHandler**(): [`PanHandler`](../interfaces/PanHandler.md)

Defined in: [board-camera/pan/pan.ts:36](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/pan/pan.ts#L36)

##### Returns

[`PanHandler`](../interfaces/PanHandler.md)

#### Set Signature

> **set** **nextHandler**(`handler`): `void`

Defined in: [board-camera/pan/pan.ts:32](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/pan/pan.ts#L32)

##### Parameters

###### handler

[`PanHandler`](../interfaces/PanHandler.md)

##### Returns

`void`

#### Implementation of

[`PanHandler`](../interfaces/PanHandler.md).[`nextHandler`](../interfaces/PanHandler.md#nexthandler)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`PanHandler`](../interfaces/PanHandler.md)

Defined in: [board-camera/pan/pan.ts:40](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/pan/pan.ts#L40)

#### Parameters

##### handler

[`PanHandler`](../interfaces/PanHandler.md)

#### Returns

[`PanHandler`](../interfaces/PanHandler.md)

#### Implementation of

[`PanHandler`](../interfaces/PanHandler.md).[`chainHandler`](../interfaces/PanHandler.md#chainhandler)

***

### panCameraBy()

> **panCameraBy**(`camera`, `delta`): `void`

Defined in: [board-camera/pan/pan.ts:51](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/pan/pan.ts#L51)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

[`PanHandler`](../interfaces/PanHandler.md).[`panCameraBy`](../interfaces/PanHandler.md#pancameraby)

***

### panCameraTo()

> **panCameraTo**(`camera`, `destination`): `void`

Defined in: [board-camera/pan/pan.ts:45](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/board-camera/pan/pan.ts#L45)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### destination

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

[`PanHandler`](../interfaces/PanHandler.md).[`panCameraTo`](../interfaces/PanHandler.md#pancamerato)
