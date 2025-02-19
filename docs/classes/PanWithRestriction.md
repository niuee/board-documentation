[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / PanWithRestriction

# Class: PanWithRestriction

Defined in: [board-camera/pan/pan.ts:108](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L108)

## Extends

- [`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md)

## Constructors

### new PanWithRestriction()

> **new PanWithRestriction**(`nextHandler`): [`PanWithRestriction`](PanWithRestriction.md)

Defined in: [board-camera/pan/pan.ts:115](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L115)

#### Parameters

##### nextHandler

[`PanHandler`](../interfaces/PanHandler.md) = `undefined`

#### Returns

[`PanWithRestriction`](PanWithRestriction.md)

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

***

### restrictRelativeXTranslation

#### Get Signature

> **get** **restrictRelativeXTranslation**(): `boolean`

Defined in: [board-camera/pan/pan.ts:139](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L139)

##### Returns

`boolean`

#### Set Signature

> **set** **restrictRelativeXTranslation**(`restrictRelativeXTranslation`): `void`

Defined in: [board-camera/pan/pan.ts:135](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L135)

##### Parameters

###### restrictRelativeXTranslation

`boolean`

##### Returns

`void`

***

### restrictRelativeYTranslation

#### Get Signature

> **get** **restrictRelativeYTranslation**(): `boolean`

Defined in: [board-camera/pan/pan.ts:147](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L147)

##### Returns

`boolean`

#### Set Signature

> **set** **restrictRelativeYTranslation**(`restrictRelativeYTranslation`): `void`

Defined in: [board-camera/pan/pan.ts:143](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L143)

##### Parameters

###### restrictRelativeYTranslation

`boolean`

##### Returns

`void`

***

### restrictXTranslation

#### Get Signature

> **get** **restrictXTranslation**(): `boolean`

Defined in: [board-camera/pan/pan.ts:123](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L123)

##### Returns

`boolean`

#### Set Signature

> **set** **restrictXTranslation**(`restrictXTranslation`): `void`

Defined in: [board-camera/pan/pan.ts:119](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L119)

##### Parameters

###### restrictXTranslation

`boolean`

##### Returns

`void`

***

### restrictYTranslation

#### Get Signature

> **get** **restrictYTranslation**(): `boolean`

Defined in: [board-camera/pan/pan.ts:131](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L131)

##### Returns

`boolean`

#### Set Signature

> **set** **restrictYTranslation**(`restrictYTranslation`): `void`

Defined in: [board-camera/pan/pan.ts:127](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L127)

##### Parameters

###### restrictYTranslation

`boolean`

##### Returns

`void`

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

### convertDeltaToComplyWithRestriction()

> **convertDeltaToComplyWithRestriction**(`camera`, `delta`): [`Point`](../type-aliases/Point.md)

Defined in: [board-camera/pan/pan.ts:151](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L151)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

[`Point`](../type-aliases/Point.md)

***

### panCameraBy()

> **panCameraBy**(`camera`, `delta`): `void`

Defined in: [board-camera/pan/pan.ts:187](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L187)

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

Defined in: [board-camera/pan/pan.ts:177](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/pan/pan.ts#L177)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### destination

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Overrides

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`panCameraTo`](PanHandlerBoilerPlate.md#pancamerato)
