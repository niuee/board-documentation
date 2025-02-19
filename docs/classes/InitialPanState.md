[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / InitialPanState

# Class: InitialPanState

Defined in: [input-state-machine/input-state-machine.ts:251](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-state-machine/input-state-machine.ts#L251)

## Extends

- [`TemplateState`](TemplateState.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

## Constructors

### new InitialPanState()

> **new InitialPanState**(): [`InitialPanState`](InitialPanState.md)

Defined in: [input-state-machine/input-state-machine.ts:253](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-state-machine/input-state-machine.ts#L253)

#### Returns

[`InitialPanState`](InitialPanState.md)

#### Overrides

[`TemplateState`](TemplateState.md).[`constructor`](TemplateState.md#constructors)

## Properties

### \_eventGuards

> `protected` **\_eventGuards**: [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardStates`](../type-aliases/BoardStates.md), [`BoardContext`](../type-aliases/BoardContext.md), [`Guard`](../type-aliases/Guard.md)\<[`BoardContext`](../type-aliases/BoardContext.md), `string`\>\>\> = `{}`

Defined in: [being/interfaces.ts:109](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L109)

#### Inherited from

[`TemplateState`](TemplateState.md).[`_eventGuards`](TemplateState.md#_eventguards)

***

### \_guards

> `protected` **\_guards**: [`Guard`](../type-aliases/Guard.md)\<[`BoardContext`](../type-aliases/BoardContext.md)\> = `{}`

Defined in: [being/interfaces.ts:108](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L108)

#### Inherited from

[`TemplateState`](TemplateState.md).[`_guards`](TemplateState.md#_guards)

## Accessors

### eventGuards

#### Get Signature

> **get** **eventGuards**(): [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<`EventPayloadMapping`, `States`, `Context`, [`Guard`](../type-aliases/Guard.md)\<`Context`, `string`\>\>\>

Defined in: [being/interfaces.ts:115](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L115)

##### Returns

[`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<`EventPayloadMapping`, `States`, `Context`, [`Guard`](../type-aliases/Guard.md)\<`Context`, `string`\>\>\>

#### Inherited from

[`TemplateState`](TemplateState.md).[`eventGuards`](TemplateState.md#eventguards)

***

### eventReactions

#### Get Signature

> **get** **eventReactions**(): [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventAction`](../type-aliases/EventAction.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>\>

Defined in: [input-state-machine/input-state-machine.ts:276](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-state-machine/input-state-machine.ts#L276)

##### Returns

[`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventAction`](../type-aliases/EventAction.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>\>

#### Overrides

[`TemplateState`](TemplateState.md).[`eventReactions`](TemplateState.md#eventreactions)

***

### guards

#### Get Signature

> **get** **guards**(): [`Guard`](../type-aliases/Guard.md)\<`Context`\>

Defined in: [being/interfaces.ts:111](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L111)

##### Returns

[`Guard`](../type-aliases/Guard.md)\<`Context`\>

#### Inherited from

[`TemplateState`](TemplateState.md).[`guards`](TemplateState.md#guards)

## Methods

### handles()

> **handles**\<`K`\>(`stateMachine`, `event`, `payload`, `context`): [`BoardStates`](../type-aliases/BoardStates.md)

Defined in: [input-state-machine/input-state-machine.ts:280](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-state-machine/input-state-machine.ts#L280)

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

#### Overrides

[`TemplateState`](TemplateState.md).[`handles`](TemplateState.md#handles)

***

### leftPointerMoveHandler()

> **leftPointerMoveHandler**(`stateMachine`, `context`, `payload`): [`BoardStates`](../type-aliases/BoardStates.md)

Defined in: [input-state-machine/input-state-machine.ts:287](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-state-machine/input-state-machine.ts#L287)

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

### leftPointerUpHandler()

> **leftPointerUpHandler**(`stateMachine`, `context`, `payload`): [`BoardStates`](../type-aliases/BoardStates.md)

Defined in: [input-state-machine/input-state-machine.ts:300](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/input-state-machine/input-state-machine.ts#L300)

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

### uponEnter()

> **uponEnter**(`stateMachine`, `context`): `void`

Defined in: [being/interfaces.ts:119](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L119)

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

Defined in: [being/interfaces.ts:123](https://github.com/niuee/board/blob/a0a1179721d4f4b943b6a9bc156753ac9737e502/src/being/interfaces.ts#L123)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

##### context

[`BoardContext`](../type-aliases/BoardContext.md)

#### Returns

`void`

#### Inherited from

[`TemplateState`](TemplateState.md).[`uponLeave`](TemplateState.md#uponleave)
