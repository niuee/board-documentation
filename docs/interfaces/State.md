[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / State

# Interface: State\<EventPayloadMapping, Context, States\>

Defined in: [being/interfaces.ts:13](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L13)

## Type Parameters

• **EventPayloadMapping**

• **Context**

• **States** *extends* `string` = `"IDLE"`

## Properties

### eventGuards

> **eventGuards**: [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<`EventPayloadMapping`, `States`, `Context`, [`Guard`](../type-aliases/Guard.md)\<`Context`, `string`\>\>\>

Defined in: [being/interfaces.ts:19](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L19)

***

### eventReactions

> **eventReactions**: [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventAction`](../type-aliases/EventAction.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

Defined in: [being/interfaces.ts:17](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L17)

***

### guards

> **guards**: [`Guard`](../type-aliases/Guard.md)\<`Context`\>

Defined in: [being/interfaces.ts:18](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L18)

## Methods

### handles()

> **handles**\<`K`\>(`stateMachine`, `event`, `payload`, `context`): `States`

Defined in: [being/interfaces.ts:16](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L16)

#### Type Parameters

• **K** *extends* `string` \| `number` \| `symbol`

#### Parameters

##### stateMachine

[`StateMachine`](StateMachine.md)\<`EventPayloadMapping`, `Context`, `States`\>

##### event

`K`

##### payload

`EventPayloadMapping`\[`K`\]

##### context

`Context`

#### Returns

`States`

***

### uponEnter()

> **uponEnter**(`stateMachine`, `context`): `void`

Defined in: [being/interfaces.ts:14](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L14)

#### Parameters

##### stateMachine

[`StateMachine`](StateMachine.md)\<`EventPayloadMapping`, `Context`, `States`\>

##### context

`Context`

#### Returns

`void`

***

### uponLeave()

> **uponLeave**(`stateMachine`, `context`): `void`

Defined in: [being/interfaces.ts:15](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L15)

#### Parameters

##### stateMachine

[`StateMachine`](StateMachine.md)\<`EventPayloadMapping`, `Context`, `States`\>

##### context

`Context`

#### Returns

`void`
