[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / createHandlerChain

# Function: createHandlerChain()

> **createHandlerChain**\<`T`, `Args`\>(...`handlers`): [`Handler`](../type-aliases/Handler.md)\<`T`, `Args`\>

Defined in: [board-camera/utils/handler-pipeline.ts:12](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/board-camera/utils/handler-pipeline.ts#L12)

Creates a handler chain from an array of handlers

## Type Parameters

• **T**

• **Args** *extends* `any`[]

## Parameters

### handlers

Array of handler functions to be chained

[`Handler`](../type-aliases/Handler.md)\<`T`, `Args`\>[] | \[[`Handler`](../type-aliases/Handler.md)\<`T`, `Args`\>[]\]

## Returns

[`Handler`](../type-aliases/Handler.md)\<`T`, `Args`\>

A single handler function that executes all handlers in sequence
