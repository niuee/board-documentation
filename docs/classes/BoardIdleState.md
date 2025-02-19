[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / BoardIdleState

# Class: BoardIdleState

Defined in: [input-state-machine/input-state-machine.ts:70](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/input-state-machine.ts#L70)

## Extends

- [`TemplateState`](TemplateState.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

## Constructors

### new BoardIdleState()

> **new BoardIdleState**(`world`): [`BoardIdleState`](BoardIdleState.md)

Defined in: [input-state-machine/input-state-machine.ts:74](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/input-state-machine.ts#L74)

#### Parameters

##### world

[`World`](../interfaces/World.md) = `...`

#### Returns

[`BoardIdleState`](BoardIdleState.md)

#### Overrides

[`TemplateState`](TemplateState.md).[`constructor`](TemplateState.md#constructors)

## Properties

### \_eventGuards

> `protected` **\_eventGuards**: [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardStates`](../type-aliases/BoardStates.md), [`BoardContext`](../type-aliases/BoardContext.md), [`Guard`](../type-aliases/Guard.md)\<[`BoardContext`](../type-aliases/BoardContext.md)\>\>\> = `{}`

Defined in: [input-state-machine/input-state-machine.ts:83](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/input-state-machine.ts#L83)

#### Overrides

[`TemplateState`](TemplateState.md).[`_eventGuards`](TemplateState.md#_eventguards)

***

### \_guards

> `protected` **\_guards**: [`Guard`](../type-aliases/Guard.md)\<[`BoardContext`](../type-aliases/BoardContext.md), `"isIdle"`\>

Defined in: [input-state-machine/input-state-machine.ts:79](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/input-state-machine.ts#L79)

#### Overrides

[`TemplateState`](TemplateState.md).[`_guards`](TemplateState.md#_guards)

## Accessors

### eventGuards

#### Get Signature

> **get** **eventGuards**(): [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<`EventPayloadMapping`, `States`, `Context`, [`Guard`](../type-aliases/Guard.md)\<`Context`, `string`\>\>\>

Defined in: [being/interfaces.ts:115](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L115)

##### Returns

[`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<`EventPayloadMapping`, `States`, `Context`, [`Guard`](../type-aliases/Guard.md)\<`Context`, `string`\>\>\>

#### Inherited from

[`TemplateState`](TemplateState.md).[`eventGuards`](TemplateState.md#eventguards)

***

### eventReactions

#### Get Signature

> **get** **eventReactions**(): [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventAction`](../type-aliases/EventAction.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>\>

Defined in: [input-state-machine/input-state-machine.ts:87](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/input-state-machine.ts#L87)

##### Returns

[`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventAction`](../type-aliases/EventAction.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>\>

#### Overrides

[`TemplateState`](TemplateState.md).[`eventReactions`](TemplateState.md#eventreactions)

***

### guards

#### Get Signature

> **get** **guards**(): [`Guard`](../type-aliases/Guard.md)\<`Context`\>

Defined in: [being/interfaces.ts:111](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L111)

##### Returns

[`Guard`](../type-aliases/Guard.md)\<`Context`\>

#### Inherited from

[`TemplateState`](TemplateState.md).[`guards`](TemplateState.md#guards)

## Methods

### handles()

> **handles**\<`K`\>(`stateMachine`, `event`, `payload`, `context`): [`BoardStates`](../type-aliases/BoardStates.md)

Defined in: [being/interfaces.ts:127](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L127)

#### Type Parameters

• **K** *extends* keyof [`BoardEventMapping`](../type-aliases/BoardEventMapping.md)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

##### event

`K`

##### payload

[`BoardEventMapping`](../type-aliases/BoardEventMapping.md)\[`K`\]

##### context

[`BoardContext`](../type-aliases/BoardContext.md)

#### Returns

[`BoardStates`](../type-aliases/BoardStates.md)

#### Inherited from

[`TemplateState`](TemplateState.md).[`handles`](TemplateState.md#handles)

***

### leftPointerDownHandler()

> **leftPointerDownHandler**(`stateMachine`, `context`, `payload`): [`BoardStates`](../type-aliases/BoardStates.md)

Defined in: [input-state-machine/input-state-machine.ts:91](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/input-state-machine.ts#L91)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

##### context

[`BoardContext`](../type-aliases/BoardContext.md)

##### payload

[`PointerEventPayload`](../type-aliases/PointerEventPayload.md)

#### Returns

[`BoardStates`](../type-aliases/BoardStates.md)

***

### leftPointerMoveHandler()

> **leftPointerMoveHandler**(`stateMachine`, `context`, `payload`): [`BoardStates`](../type-aliases/BoardStates.md)

Defined in: [input-state-machine/input-state-machine.ts:98](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/input-state-machine.ts#L98)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

##### context

[`BoardContext`](../type-aliases/BoardContext.md)

##### payload

[`PointerEventPayload`](../type-aliases/PointerEventPayload.md)

#### Returns

[`BoardStates`](../type-aliases/BoardStates.md)

***

### middlePointerDownHandler()

> **middlePointerDownHandler**(`stateMachine`, `context`, `payload`): [`BoardStates`](../type-aliases/BoardStates.md)

Defined in: [input-state-machine/input-state-machine.ts:146](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/input-state-machine.ts#L146)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

##### context

[`BoardContext`](../type-aliases/BoardContext.md)

##### payload

[`PointerEventPayload`](../type-aliases/PointerEventPayload.md)

#### Returns

[`BoardStates`](../type-aliases/BoardStates.md)

***

### scrollHandler()

> **scrollHandler**(`stateMachine`, `context`, `payload`): [`BoardStates`](../type-aliases/BoardStates.md)

Defined in: [input-state-machine/input-state-machine.ts:123](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/input-state-machine.ts#L123)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

##### context

[`BoardContext`](../type-aliases/BoardContext.md)

##### payload

[`ScrollEventPayload`](../type-aliases/ScrollEventPayload.md)

#### Returns

[`BoardStates`](../type-aliases/BoardStates.md)

***

### scrollWithCtrlHandler()

> **scrollWithCtrlHandler**(`stateMachine`, `context`, `payload`): [`BoardStates`](../type-aliases/BoardStates.md)

Defined in: [input-state-machine/input-state-machine.ts:128](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/input-state-machine.ts#L128)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

##### context

[`BoardContext`](../type-aliases/BoardContext.md)

##### payload

[`ScrollWithCtrlEventPayload`](../type-aliases/ScrollWithCtrlEventPayload.md)

#### Returns

[`BoardStates`](../type-aliases/BoardStates.md)

***

### spacebarDownHandler()

> **spacebarDownHandler**(`stateMachine`, `context`, `payload`): [`BoardStates`](../type-aliases/BoardStates.md)

Defined in: [input-state-machine/input-state-machine.ts:141](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/input-state-machine.ts#L141)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

##### context

[`BoardContext`](../type-aliases/BoardContext.md)

##### payload

[`SpaceBarEventPayload`](../type-aliases/SpaceBarEventPayload.md)

#### Returns

[`BoardStates`](../type-aliases/BoardStates.md)

***

### uponEnter()

> **uponEnter**(`stateMachine`, `context`): `void`

Defined in: [being/interfaces.ts:119](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L119)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

##### context

[`BoardContext`](../type-aliases/BoardContext.md)

#### Returns

`void`

#### Inherited from

[`TemplateState`](TemplateState.md).[`uponEnter`](TemplateState.md#uponenter)

***

### uponLeave()

> **uponLeave**(`stateMachine`, `context`): `void`

Defined in: [being/interfaces.ts:123](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L123)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

##### context

[`BoardContext`](../type-aliases/BoardContext.md)

#### Returns

`void`

#### Inherited from

[`TemplateState`](TemplateState.md).[`uponLeave`](TemplateState.md#uponleave)
