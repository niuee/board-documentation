[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / EventAction

# Type Alias: EventAction\<EventPayloadMapping, Context, States\>

> **EventAction**\<`EventPayloadMapping`, `Context`, `States`\>: `{ [K in keyof EventPayloadMapping]: { action: (stateMachine: StateMachine<EventPayloadMapping, Context, States>, context: Context, event: EventPayloadMapping[K]) => States; defaultTargetState: States } }`

Defined in: [being/interfaces.ts:22](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L22)

## Type Parameters

• **EventPayloadMapping**

• **Context**

• **States** *extends* `string`
