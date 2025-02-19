[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / EventGuards

# Type Alias: EventGuards\<EventPayloadMapping, States, Context, T\>

> **EventGuards**\<`EventPayloadMapping`, `States`, `Context`, `T`\>: `{ [K in keyof EventPayloadMapping]: GuardMapping<Context, T, States>[] }`

Defined in: [being/interfaces.ts:40](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L40)

## Type Parameters

• **EventPayloadMapping**

• **States** *extends* `string`

• **Context**

• **T** *extends* [`Guard`](Guard.md)\<`Context`\>
