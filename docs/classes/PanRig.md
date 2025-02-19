[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / PanRig

# Class: PanRig

Defined in: [board-camera/pan/pan.ts:193](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L193)

## Extends

- [`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md)

## Implements

- [`PanController`](../interfaces/PanController.md)

## Constructors

### new PanRig()

> **new PanRig**(): [`PanRig`](PanRig.md)

Defined in: [board-camera/pan/pan.ts:249](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L249)

#### Returns

[`PanRig`](PanRig.md)

#### Overrides

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`constructor`](PanHandlerBoilerPlate.md#constructors)

## Properties

### \_nextHandler?

> `protected` `optional` **\_nextHandler**: [`PanHandler`](../interfaces/PanHandler.md)

Defined in: [board-camera/pan/pan.ts:25](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L25)

#### Inherited from

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`_nextHandler`](PanHandlerBoilerPlate.md#_nexthandler)

## Accessors

### limitEntireViewPort

#### Get Signature

> **get** **limitEntireViewPort**(): `boolean`

Defined in: [board-camera/pan/pan.ts:245](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L245)

##### Returns

`boolean`

#### Set Signature

> **set** **limitEntireViewPort**(`limitEntireViewPort`): `void`

Defined in: [board-camera/pan/pan.ts:241](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L241)

##### Parameters

###### limitEntireViewPort

`boolean`

##### Returns

`void`

#### Implementation of

[`PanController`](../interfaces/PanController.md).[`limitEntireViewPort`](../interfaces/PanController.md#limitentireviewport)

***

### nextHandler

#### Get Signature

> **get** **nextHandler**(): [`PanHandler`](../interfaces/PanHandler.md)

Defined in: [board-camera/pan/pan.ts:36](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L36)

##### Returns

[`PanHandler`](../interfaces/PanHandler.md)

#### Set Signature

> **set** **nextHandler**(`handler`): `void`

Defined in: [board-camera/pan/pan.ts:32](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L32)

##### Parameters

###### handler

[`PanHandler`](../interfaces/PanHandler.md)

##### Returns

`void`

#### Implementation of

[`PanController`](../interfaces/PanController.md).[`nextHandler`](../interfaces/PanController.md#nexthandler)

#### Inherited from

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`nextHandler`](PanHandlerBoilerPlate.md#nexthandler-1)

***

### restrictRelativeXTranslation

#### Get Signature

> **get** **restrictRelativeXTranslation**(): `boolean`

Defined in: [board-camera/pan/pan.ts:233](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L233)

##### Returns

`boolean`

#### Set Signature

> **set** **restrictRelativeXTranslation**(`restrictRelativeXTranslation`): `void`

Defined in: [board-camera/pan/pan.ts:199](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L199)

##### Parameters

###### restrictRelativeXTranslation

`boolean`

##### Returns

`void`

#### Implementation of

[`PanController`](../interfaces/PanController.md).[`restrictRelativeXTranslation`](../interfaces/PanController.md#restrictrelativextranslation)

***

### restrictRelativeYTranslation

#### Get Signature

> **get** **restrictRelativeYTranslation**(): `boolean`

Defined in: [board-camera/pan/pan.ts:237](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L237)

##### Returns

`boolean`

#### Set Signature

> **set** **restrictRelativeYTranslation**(`restrictRelativeYTranslation`): `void`

Defined in: [board-camera/pan/pan.ts:203](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L203)

##### Parameters

###### restrictRelativeYTranslation

`boolean`

##### Returns

`void`

#### Implementation of

[`PanController`](../interfaces/PanController.md).[`restrictRelativeYTranslation`](../interfaces/PanController.md#restrictrelativeytranslation)

***

### restrictTranslation

#### Get Signature

> **get** **restrictTranslation**(): `boolean`

Defined in: [board-camera/pan/pan.ts:221](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L221)

##### Returns

`boolean`

#### Set Signature

> **set** **restrictTranslation**(`restrictTranslation`): `void`

Defined in: [board-camera/pan/pan.ts:215](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L215)

##### Parameters

###### restrictTranslation

`boolean`

##### Returns

`void`

#### Implementation of

[`PanController`](../interfaces/PanController.md).[`restrictTranslation`](../interfaces/PanController.md#restricttranslation)

***

### restrictXTranslation

#### Get Signature

> **get** **restrictXTranslation**(): `boolean`

Defined in: [board-camera/pan/pan.ts:225](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L225)

##### Returns

`boolean`

#### Set Signature

> **set** **restrictXTranslation**(`restrictXTranslation`): `void`

Defined in: [board-camera/pan/pan.ts:207](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L207)

##### Parameters

###### restrictXTranslation

`boolean`

##### Returns

`void`

#### Implementation of

[`PanController`](../interfaces/PanController.md).[`restrictXTranslation`](../interfaces/PanController.md#restrictxtranslation)

***

### restrictYTranslation

#### Get Signature

> **get** **restrictYTranslation**(): `boolean`

Defined in: [board-camera/pan/pan.ts:229](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L229)

##### Returns

`boolean`

#### Set Signature

> **set** **restrictYTranslation**(`restrictYTranslation`): `void`

Defined in: [board-camera/pan/pan.ts:211](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L211)

##### Parameters

###### restrictYTranslation

`boolean`

##### Returns

`void`

#### Implementation of

[`PanController`](../interfaces/PanController.md).[`restrictYTranslation`](../interfaces/PanController.md#restrictytranslation)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`PanHandler`](../interfaces/PanHandler.md)

Defined in: [board-camera/pan/pan.ts:40](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L40)

#### Parameters

##### handler

[`PanHandler`](../interfaces/PanHandler.md)

#### Returns

[`PanHandler`](../interfaces/PanHandler.md)

#### Implementation of

[`PanController`](../interfaces/PanController.md).[`chainHandler`](../interfaces/PanController.md#chainhandler)

#### Inherited from

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`chainHandler`](PanHandlerBoilerPlate.md#chainhandler)

***

### panCameraBy()

> **panCameraBy**(`camera`, `delta`): `void`

Defined in: [board-camera/pan/pan.ts:51](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L51)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### delta

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

[`PanController`](../interfaces/PanController.md).[`panCameraBy`](../interfaces/PanController.md#pancameraby)

#### Inherited from

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`panCameraBy`](PanHandlerBoilerPlate.md#pancameraby)

***

### panCameraTo()

> **panCameraTo**(`camera`, `destination`): `void`

Defined in: [board-camera/pan/pan.ts:45](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/pan/pan.ts#L45)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### destination

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

#### Implementation of

[`PanController`](../interfaces/PanController.md).[`panCameraTo`](../interfaces/PanController.md#pancamerato)

#### Inherited from

[`PanHandlerBoilerPlate`](PanHandlerBoilerPlate.md).[`panCameraTo`](PanHandlerBoilerPlate.md#pancamerato)
