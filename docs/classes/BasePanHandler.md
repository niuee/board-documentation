[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / BasePanHandler

# Class: BasePanHandler

Defined in: [board-camera/pan/pan.ts:58](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L58)

## Extends

- [`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md)

## Constructors

### new BasePanHandler()

> **new BasePanHandler**(`nextHandler`): [`BasePanHandler`](BasePanHandler.md)

Defined in: [board-camera/pan/pan.ts:61](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L61)

#### Parameters

##### nextHandler

[`PanHandler`](../interfaces/PanHandler.md) = `undefined`

#### Returns

[`BasePanHandler`](BasePanHandler.md)

#### Overrides

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`constructor`](PanHandlerBoilerPlate.md#constructors)

## Properties

### \_nextHandler?

> `protected` `optional` **\_nextHandler**: [`PanHandler`](../interfaces/PanHandler.md)

Defined in: [board-camera/pan/pan.ts:25](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L25)

#### Inherited from

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`_nextHandler`](PanHandlerBoilerPlate.md#_nexthandler)

## Accessors

### nextHandler

#### Get Signature

> **get** **nextHandler**(): [`PanHandler`](../interfaces/PanHandler.md)

Defined in: [board-camera/pan/pan.ts:36](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L36)

##### Returns

[`PanHandler`](../interfaces/PanHandler.md)

#### Set Signature

> **set** **nextHandler**(`handler`): `void`

Defined in: [board-camera/pan/pan.ts:32](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L32)

##### Parameters

###### handler

[`PanHandler`](../interfaces/PanHandler.md)

##### Returns

`void`

#### Inherited from

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`nextHandler`](PanHandlerBoilerPlate.md#nexthandler-1)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`PanHandler`](../interfaces/PanHandler.md)

Defined in: [board-camera/pan/pan.ts:40](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L40)

#### Parameters

##### handler

[`PanHandler`](../interfaces/PanHandler.md)

#### Returns

[`PanHandler`](../interfaces/PanHandler.md)

#### Inherited from

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`chainHandler`](PanHandlerBoilerPlate.md#chainhandler)

***

### panCameraBy()

> **panCameraBy**(`camera`, `diff`): `void`

Defined in: [board-camera/pan/pan.ts:69](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L69)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### diff

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Overrides

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`panCameraBy`](PanHandlerBoilerPlate.md#pancameraby)

***

### panCameraTo()

> **panCameraTo**(`camera`, `destination`): `void`

Defined in: [board-camera/pan/pan.ts:65](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L65)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### destination

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Overrides

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`panCameraTo`](PanHandlerBoilerPlate.md#pancamerato)
