[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / ClampHandler

# Class: ClampHandler

Defined in: [board-camera/pan/pan.ts:74](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/pan/pan.ts#L74)

## Extends

- [`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md)

## Constructors

### new ClampHandler()

> **new ClampHandler**(`nextHandler`): [`ClampHandler`](ClampHandler.md)

Defined in: [board-camera/pan/pan.ts:78](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/pan/pan.ts#L78)

#### Parameters

##### nextHandler

[`PanHandler`](../interfaces/PanHandler.md) = `undefined`

#### Returns

[`ClampHandler`](ClampHandler.md)

#### Overrides

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`constructor`](PanHandlerBoilerPlate.md#constructors)

## Properties

### \_nextHandler?

> `protected` `optional` **\_nextHandler**: [`PanHandler`](../interfaces/PanHandler.md)

Defined in: [board-camera/pan/pan.ts:25](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/pan/pan.ts#L25)

#### Inherited from

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`_nextHandler`](PanHandlerBoilerPlate.md#_nexthandler)

## Accessors

### entireViewPort

#### Get Signature

> **get** **entireViewPort**(): `boolean`

Defined in: [board-camera/pan/pan.ts:86](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/pan/pan.ts#L86)

##### Returns

`boolean`

#### Set Signature

> **set** **entireViewPort**(`entireViewPort`): `void`

Defined in: [board-camera/pan/pan.ts:82](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/pan/pan.ts#L82)

##### Parameters

###### entireViewPort

`boolean`

##### Returns

`void`

***

### nextHandler

#### Get Signature

> **get** **nextHandler**(): [`PanHandler`](../interfaces/PanHandler.md)

Defined in: [board-camera/pan/pan.ts:36](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/pan/pan.ts#L36)

##### Returns

[`PanHandler`](../interfaces/PanHandler.md)

#### Set Signature

> **set** **nextHandler**(`handler`): `void`

Defined in: [board-camera/pan/pan.ts:32](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/pan/pan.ts#L32)

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

Defined in: [board-camera/pan/pan.ts:40](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/pan/pan.ts#L40)

#### Parameters

##### handler

[`PanHandler`](../interfaces/PanHandler.md)

#### Returns

[`PanHandler`](../interfaces/PanHandler.md)

#### Inherited from

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`chainHandler`](PanHandlerBoilerPlate.md#chainhandler)

***

### panCameraBy()

> **panCameraBy**(`camera`, `delta`): `void`

Defined in: [board-camera/pan/pan.ts:98](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/pan/pan.ts#L98)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Overrides

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`panCameraBy`](PanHandlerBoilerPlate.md#pancameraby)

***

### panCameraTo()

> **panCameraTo**(`camera`, `destination`): `void`

Defined in: [board-camera/pan/pan.ts:90](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/board-camera/pan/pan.ts#L90)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### destination

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Overrides

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`panCameraTo`](PanHandlerBoilerPlate.md#pancamerato)
