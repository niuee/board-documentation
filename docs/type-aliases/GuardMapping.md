[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / GuardMapping

# Type Alias: GuardMapping\<Context, G, States\>

> **GuardMapping**\<`Context`, `G`, `States`\>: `object`

Defined in: [being/interfaces.ts:35](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L35)

## Type Parameters

• **Context**

• **G**

• **States** *extends* `string`

## Type declaration

### guard

> **guard**: `G` *extends* [`Guard`](Guard.md)\<`Context`, infer K\> ? `K` : `never`

### target

> **target**: `States`
