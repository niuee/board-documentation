[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / GuardMapping

# Type Alias: GuardMapping\<Context, G, States\>

> **GuardMapping**\<`Context`, `G`, `States`\>: `object`

Defined in: [being/interfaces.ts:35](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L35)

## Type Parameters

• **Context**

• **G**

• **States** *extends* `string`

## Type declaration

### guard

> **guard**: `G` *extends* [`Guard`](Guard.md)\<`Context`, infer K\> ? `K` : `never`

### target

> **target**: `States`
