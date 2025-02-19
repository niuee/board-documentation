[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / EventAction

# Type Alias: EventAction\<EventPayloadMapping, Context, States\>

> **EventAction**\<`EventPayloadMapping`, `Context`, `States`\>: `{ [K in keyof EventPayloadMapping]: { action: (stateMachine: StateMachine<EventPayloadMapping, Context, States>, context: Context, event: EventPayloadMapping[K]) => States; defaultTargetState: States } }`

Defined in: [being/interfaces.ts:22](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L22)

## Type Parameters

• **EventPayloadMapping**

• **Context**

• **States** *extends* `string`
