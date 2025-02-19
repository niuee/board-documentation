[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / EventAction

# Type Alias: EventAction\<EventPayloadMapping, Context, States\>

> **EventAction**\<`EventPayloadMapping`, `Context`, `States`\>: `{ [K in keyof EventPayloadMapping]: { action: (stateMachine: StateMachine<EventPayloadMapping, Context, States>, context: Context, event: EventPayloadMapping[K]) => States; defaultTargetState: States } }`

Defined in: [being/interfaces.ts:22](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L22)

## Type Parameters

• **EventPayloadMapping**

• **Context**

• **States** *extends* `string`
