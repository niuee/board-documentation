[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / StateMachine

# Interface: StateMachine\<EventPayloadMapping, Context, States\>

Defined in: [being/interfaces.ts:1](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L1)

## Type Parameters

• **EventPayloadMapping**

• **Context**

• **States** *extends* `string` = `"IDLE"`

## Properties

### possibleStates

> **possibleStates**: `States`[]

Defined in: [being/interfaces.ts:7](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L7)

***

### states

> **states**: [`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<`States`, [`State`](State.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

Defined in: [being/interfaces.ts:5](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L5)

## Methods

### happens()

> **happens**\<`K`\>(`event`, `payload`, `context`): `States`

Defined in: [being/interfaces.ts:3](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L3)

#### Type Parameters

• **K** *extends* `string` \| `number` \| `symbol`

#### Parameters

##### event

`K`

##### payload

`EventPayloadMapping`\[`K`\]

##### context

`Context`

#### Returns

`States`

***

### onHappens()

> **onHappens**(`callback`): `void`

Defined in: [being/interfaces.ts:8](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L8)

#### Parameters

##### callback

(`event`, `payload`, `context`) => `void`

#### Returns

`void`

***

### onStateChange()

> **onStateChange**(`callback`): `void`

Defined in: [being/interfaces.ts:6](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L6)

#### Parameters

##### callback

[`StateChangeCallback`](../type-aliases/StateChangeCallback.md)\<`EventPayloadMapping`, `Context`, `States`\>

#### Returns

`void`

***

### setContext()

> **setContext**(`context`): `void`

Defined in: [being/interfaces.ts:4](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L4)

#### Parameters

##### context

`Context`

#### Returns

`void`

***

### switchTo()

> **switchTo**(`state`): `void`

Defined in: [being/interfaces.ts:2](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L2)

#### Parameters

##### state

`States`

#### Returns

`void`
