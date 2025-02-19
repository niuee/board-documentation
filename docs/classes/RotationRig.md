[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / RotationRig

# Class: RotationRig

Defined in: [board-camera/rotation/rotation.ts:122](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L122)

## Extends

- [`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md)

## Implements

- [`RotationController`](../interfaces/RotationController.md)

## Constructors

### new RotationRig()

> **new RotationRig**(`nextHandler`): [`RotationRig`](RotationRig.md)

Defined in: [board-camera/rotation/rotation.ts:136](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L136)

#### Parameters

##### nextHandler

[`RotationHandler`](../interfaces/RotationHandler.md) = `undefined`

#### Returns

[`RotationRig`](RotationRig.md)

#### Overrides

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md).[`constructor`](RotationHandlerBoilerPlate.md#constructors)

## Accessors

### nextHandler

#### Get Signature

> **get** **nextHandler**(): [`RotationHandler`](../interfaces/RotationHandler.md)

Defined in: [board-camera/rotation/rotation.ts:27](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L27)

##### Returns

[`RotationHandler`](../interfaces/RotationHandler.md)

#### Set Signature

> **set** **nextHandler**(`handler`): `void`

Defined in: [board-camera/rotation/rotation.ts:23](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L23)

##### Parameters

###### handler

[`RotationHandler`](../interfaces/RotationHandler.md)

##### Returns

`void`

#### Implementation of

[`RotationController`](../interfaces/RotationController.md).[`nextHandler`](../interfaces/RotationController.md#nexthandler)

#### Inherited from

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md).[`nextHandler`](RotationHandlerBoilerPlate.md#nexthandler-1)

***

### restrictRotation

#### Get Signature

> **get** **restrictRotation**(): `boolean`

Defined in: [board-camera/rotation/rotation.ts:128](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L128)

##### Returns

`boolean`

#### Set Signature

> **set** **restrictRotation**(`restrictRotation`): `void`

Defined in: [board-camera/rotation/rotation.ts:132](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L132)

##### Parameters

###### restrictRotation

`boolean`

##### Returns

`void`

#### Implementation of

[`RotationController`](../interfaces/RotationController.md).[`restrictRotation`](../interfaces/RotationController.md#restrictrotation)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`RotationHandler`](../interfaces/RotationHandler.md)

Defined in: [board-camera/rotation/rotation.ts:31](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L31)

#### Parameters

##### handler

[`RotationHandler`](../interfaces/RotationHandler.md)

#### Returns

[`RotationHandler`](../interfaces/RotationHandler.md)

#### Implementation of

[`RotationController`](../interfaces/RotationController.md).[`chainHandler`](../interfaces/RotationController.md#chainhandler)

#### Inherited from

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md).[`chainHandler`](RotationHandlerBoilerPlate.md#chainhandler)

***

### rotateCameraBy()

> **rotateCameraBy**(`camera`, `diff`): `void`

Defined in: [board-camera/rotation/rotation.ts:143](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L143)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### diff

`number`

#### Returns

`void`

#### Implementation of

[`RotationController`](../interfaces/RotationController.md).[`rotateCameraBy`](../interfaces/RotationController.md#rotatecameraby)

#### Overrides

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md).[`rotateCameraBy`](RotationHandlerBoilerPlate.md#rotatecameraby)

***

### rotateCameraTo()

> **rotateCameraTo**(`camera`, `targetRotation`): `void`

Defined in: [board-camera/rotation/rotation.ts:148](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L148)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### targetRotation

`number`

#### Returns

`void`

#### Implementation of

[`RotationController`](../interfaces/RotationController.md).[`rotateCameraTo`](../interfaces/RotationController.md#rotatecamerato)

#### Overrides

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md).[`rotateCameraTo`](RotationHandlerBoilerPlate.md#rotatecamerato)
