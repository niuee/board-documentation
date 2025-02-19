[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / EventGuards

# Type Alias: EventGuards\<EventPayloadMapping, States, Context, T\>

> **EventGuards**\<`EventPayloadMapping`, `States`, `Context`, `T`\>: `{ [K in keyof EventPayloadMapping]: GuardMapping<Context, T, States>[] }`

Defined in: [being/interfaces.ts:40](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L40)

## Type Parameters

• **EventPayloadMapping**

• **States** *extends* `string`

• **Context**

• **T** *extends* [`Guard`](Guard.md)\<`Context`\>
