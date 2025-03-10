[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / RotationHandler

# Interface: RotationHandler

Defined in: [board-camera/rotation/rotation.ts:4](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L4)

## Extended by

- [`RotationController`](RotationController.md)

## Properties

### nextHandler?

> `optional` **nextHandler**: [`RotationHandler`](RotationHandler.md)

Defined in: [board-camera/rotation/rotation.ts:5](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L5)

## Methods

### chainHandler()

> **chainHandler**(`handler`): [`RotationHandler`](RotationHandler.md)

Defined in: [board-camera/rotation/rotation.ts:6](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L6)

#### Parameters

##### handler

[`RotationHandler`](RotationHandler.md)

#### Returns

[`RotationHandler`](RotationHandler.md)

***

### rotateCameraBy()

> **rotateCameraBy**(`camera`, `delta`): `void`

Defined in: [board-camera/rotation/rotation.ts:8](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L8)

#### Parameters

##### camera

[`BoardCamera`](BoardCamera.md)

##### delta

`number`

#### Returns

`void`

***

### rotateCameraTo()

> **rotateCameraTo**(`camera`, `targetRotation`): `void`

Defined in: [board-camera/rotation/rotation.ts:7](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/board-camera/rotation/rotation.ts#L7)

#### Parameters

##### camera

[`BoardCamera`](BoardCamera.md)

##### targetRotation

`number`

#### Returns

`void`
