[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / RotationRestrictionHandler

# Class: RotationRestrictionHandler

Defined in: [board-camera/rotation/rotation.ts:69](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L69)

## Extends

- [`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md)

## Constructors

### new RotationRestrictionHandler()

> **new RotationRestrictionHandler**(`nextHandler`): [`RotationRestrictionHandler`](RotationRestrictionHandler.md)

Defined in: [board-camera/rotation/rotation.ts:73](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L73)

#### Parameters

##### nextHandler

[`RotationHandler`](../interfaces/RotationHandler.md) = `undefined`

#### Returns

[`RotationRestrictionHandler`](RotationRestrictionHandler.md)

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

***

### restrictRotation

#### Get Signature

> **get** **restrictRotation**(): `boolean`

Defined in: [board-camera/rotation/rotation.ts:77](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L77)

##### Returns

`boolean`

#### Set Signature

> **set** **restrictRotation**(`restrictRotation`): `void`

Defined in: [board-camera/rotation/rotation.ts:81](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L81)

##### Parameters

###### restrictRotation

`boolean`

##### Returns

`void`

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

Defined in: [board-camera/rotation/rotation.ts:85](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L85)

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

Defined in: [board-camera/rotation/rotation.ts:92](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L92)

#### Parameters

##### camera

[`BoardCamera`](../interfaces/BoardCamera.md)

##### targetRotation

`number`

#### Returns

`void`

#### Overrides

[`RotationHandlerBoilerPlate`](RotationHandlerBoilerPlate.md).[`rotateCameraTo`](RotationHandlerBoilerPlate.md#rotatecamerato)
