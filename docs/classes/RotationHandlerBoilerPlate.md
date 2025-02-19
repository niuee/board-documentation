[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / RotationHandlerBoilerPlate

# Class: `abstract` RotationHandlerBoilerPlate

Defined in: [board-camera/rotation/rotation.ts:15](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L15)

## Extended by

- [`BaseRotationHandler`](BaseRotationHandler.md)
- [`RotationRestrictionHandler`](RotationRestrictionHandler.md)
- [`RotationClampHandler`](RotationClampHandler.md)
- [`RotationRig`](RotationRig.md)

## Implements

- [`RotationHandler`](../interfaces/RotationHandler.md)

## Constructors

### new RotationHandlerBoilerPlate()

> **new RotationHandlerBoilerPlate**(`nextHandler`): [`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md)

Defined in: [board-camera/rotation/rotation.ts:19](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L19)

#### Parameters

##### nextHandler

[`RotationHandler`](../interfaces/RotationHandler.md) = `undefined`

#### Returns

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md)

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

#### Implementation of

[`RotationHandler`](../interfaces/RotationHandler.md).[`nextHandler`](../interfaces/RotationHandler.md#nexthandler)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`RotationHandler`](../interfaces/RotationHandler.md)

Defined in: [board-camera/rotation/rotation.ts:31](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L31)

#### Parameters

##### handler

[`RotationHandler`](../interfaces/RotationHandler.md)

#### Returns

[`RotationHandler`](../interfaces/RotationHandler.md)

#### Implementation of

[`RotationHandler`](../interfaces/RotationHandler.md).[`chainHandler`](../interfaces/RotationHandler.md#chainhandler)

***

### rotateCameraBy()

> **rotateCameraBy**(`camera`, `delta`): `void`

Defined in: [board-camera/rotation/rotation.ts:42](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L42)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### delta

`number`

#### Returns

`void`

#### Implementation of

[`RotationHandler`](../interfaces/RotationHandler.md).[`rotateCameraBy`](../interfaces/RotationHandler.md#rotatecameraby)

***

### rotateCameraTo()

> **rotateCameraTo**(`camera`, `targetRotation`): `void`

Defined in: [board-camera/rotation/rotation.ts:36](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L36)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### targetRotation

`number`

#### Returns

`void`

#### Implementation of

[`RotationHandler`](../interfaces/RotationHandler.md).[`rotateCameraTo`](../interfaces/RotationHandler.md#rotatecamerato)
