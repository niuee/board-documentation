[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / BaseRotationHandler

# Class: BaseRotationHandler

Defined in: [board-camera/rotation/rotation.ts:50](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L50)

## Extends

- [`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md)

## Constructors

### new BaseRotationHandler()

> **new BaseRotationHandler**(`nextHandler`): [`BaseRotationHandler`](BaseRotationHandler.md)

Defined in: [board-camera/rotation/rotation.ts:52](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L52)

#### Parameters

##### nextHandler

[`RotationHandler`](../interfaces/RotationHandler.md) = `undefined`

#### Returns

[`BaseRotationHandler`](BaseRotationHandler.md)

#### Overrides

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md).[`constructor`](RotationHandlerBoilerPlate.md#constructors)

## Accessors

### nextHandler

#### Get Signature

> **get** **nextHandler**(): [`RotationHandler`](../interfaces/RotationHandler.md)

Defined in: [board-camera/rotation/rotation.ts:27](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L27)

##### Returns

[`RotationHandler`](../interfaces/RotationHandler.md)

#### Set Signature

> **set** **nextHandler**(`handler`): `void`

Defined in: [board-camera/rotation/rotation.ts:23](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L23)

##### Parameters

###### handler

[`RotationHandler`](../interfaces/RotationHandler.md)

##### Returns

`void`

#### Inherited from

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md).[`nextHandler`](RotationHandlerBoilerPlate.md#nexthandler-1)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`RotationHandler`](../interfaces/RotationHandler.md)

Defined in: [board-camera/rotation/rotation.ts:31](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L31)

#### Parameters

##### handler

[`RotationHandler`](../interfaces/RotationHandler.md)

#### Returns

[`RotationHandler`](../interfaces/RotationHandler.md)

#### Inherited from

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md).[`chainHandler`](RotationHandlerBoilerPlate.md#chainhandler)

***

### rotateCameraBy()

> **rotateCameraBy**(`camera`, `diff`): `void`

Defined in: [board-camera/rotation/rotation.ts:61](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L61)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### diff

`number`

#### Returns

`void`

#### Overrides

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md).[`rotateCameraBy`](RotationHandlerBoilerPlate.md#rotatecameraby)

***

### rotateCameraTo()

> **rotateCameraTo**(`camera`, `targetRotation`): `void`

Defined in: [board-camera/rotation/rotation.ts:56](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L56)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### targetRotation

`number`

#### Returns

`void`

#### Overrides

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md).[`rotateCameraTo`](RotationHandlerBoilerPlate.md#rotatecamerato)
