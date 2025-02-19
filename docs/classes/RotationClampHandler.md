[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / RotationClampHandler

# Class: RotationClampHandler

Defined in: [board-camera/rotation/rotation.ts:100](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L100)

## Extends

- [`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md)

## Constructors

### new RotationClampHandler()

> **new RotationClampHandler**(`nextHandler`): [`RotationClampHandler`](RotationClampHandler.md)

Defined in: [board-camera/rotation/rotation.ts:103](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L103)

#### Parameters

##### nextHandler

[`RotationHandler`](../interfaces/RotationHandler.md) = `undefined`

#### Returns

[`RotationClampHandler`](RotationClampHandler.md)

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

#### Inherited from

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md).[`nextHandler`](RotationHandlerBoilerPlate.md#nexthandler-1)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`RotationHandler`](../interfaces/RotationHandler.md)

Defined in: [board-camera/rotation/rotation.ts:31](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L31)

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

Defined in: [board-camera/rotation/rotation.ts:107](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L107)

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

Defined in: [board-camera/rotation/rotation.ts:115](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/rotation/rotation.ts#L115)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### targetRotation

`number`

#### Returns

`void`

#### Overrides

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md).[`rotateCameraTo`](RotationHandlerBoilerPlate.md#rotatecamerato)
