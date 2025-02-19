[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / BoardWorld

# Class: BoardWorld

Defined in: [input-state-machine/input-state-machine.ts:432](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/input-state-machine.ts#L432)

## Implements

- [`World`](../interfaces/World.md)

## Constructors

### new BoardWorld()

> **new BoardWorld**(): [`BoardWorld`](BoardWorld.md)

#### Returns

[`BoardWorld`](BoardWorld.md)

## Methods

### processPoint()

> **processPoint**(`stateMachine`, `point`): `boolean`

Defined in: [input-state-machine/input-state-machine.ts:433](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/input-state-machine.ts#L433)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

##### point

[`Point`](../type-aliases/Point.md)

#### Returns

`boolean`

#### Implementation of

[`World`](../interfaces/World.md).[`processPoint`](../interfaces/World.md#processpoint)
