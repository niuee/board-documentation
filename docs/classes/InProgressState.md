[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / InProgressState

# Class: InProgressState

Defined in: [input-state-machine/touch-state-machine.ts:144](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/touch-state-machine.ts#L144)

## Extends

- [`TemplateState`](TemplateState.md)\<[`TouchEventMapping`](../type-aliases/TouchEventMapping.md), [`TouchContext`](../interfaces/TouchContext.md), [`TouchStates`](../type-aliases/TouchStates.md)\>

## Constructors

### new InProgressState()

> **new InProgressState**(): [`InProgressState`](InProgressState.md)

#### Returns

[`InProgressState`](InProgressState.md)

#### Inherited from

[`TemplateState`](TemplateState.md).[`constructor`](TemplateState.md#constructors)

## Properties

### \_eventGuards

> `protected` **\_eventGuards**: [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<[`TouchEventMapping`](../type-aliases/TouchEventMapping.md), [`TouchStates`](../type-aliases/TouchStates.md), [`TouchContext`](../interfaces/TouchContext.md), [`Guard`](../type-aliases/Guard.md)\<[`TouchContext`](../interfaces/TouchContext.md), `string`\>\>\> = `{}`

Defined in: [being/interfaces.ts:109](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L109)

#### Inherited from

[`TemplateState`](TemplateState.md).[`_eventGuards`](TemplateState.md#_eventguards)

***

### \_guards

> `protected` **\_guards**: [`Guard`](../type-aliases/Guard.md)\<[`TouchContext`](../interfaces/TouchContext.md)\> = `{}`

Defined in: [being/interfaces.ts:108](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L108)

#### Inherited from

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

> **get** **eventReactions**(): [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventAction`](../type-aliases/EventAction.md)\<[`TouchEventMapping`](../type-aliases/TouchEventMapping.md), [`TouchContext`](../interfaces/TouchContext.md), [`TouchStates`](../type-aliases/TouchStates.md)\>\>

Defined in: [input-state-machine/touch-state-machine.ts:157](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/touch-state-machine.ts#L157)

##### Returns

[`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventAction`](../type-aliases/EventAction.md)\<[`TouchEventMapping`](../type-aliases/TouchEventMapping.md), [`TouchContext`](../interfaces/TouchContext.md), [`TouchStates`](../type-aliases/TouchStates.md)\>\>

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

> **handles**\<`K`\>(`stateMachine`, `event`, `payload`, `context`): [`TouchStates`](../type-aliases/TouchStates.md)

Defined in: [being/interfaces.ts:127](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L127)

#### Type Parameters

• **K** *extends* keyof [`TouchEventMapping`](../type-aliases/TouchEventMapping.md)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`TouchEventMapping`](../type-aliases/TouchEventMapping.md), [`TouchContext`](../interfaces/TouchContext.md), [`TouchStates`](../type-aliases/TouchStates.md)\>

##### event

`K`

##### payload

[`TouchEventMapping`](../type-aliases/TouchEventMapping.md)\[`K`\]

##### context

[`TouchContext`](../interfaces/TouchContext.md)

#### Returns

[`TouchStates`](../type-aliases/TouchStates.md)

#### Inherited from

[`TemplateState`](TemplateState.md).[`handles`](TemplateState.md#handles)

***

### touchend()

> **touchend**(`stateMachine`, `context`, `payload`): [`TouchStates`](../type-aliases/TouchStates.md)

Defined in: [input-state-machine/touch-state-machine.ts:187](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/touch-state-machine.ts#L187)

#### Parameters

##### stateMachine

`TouchStateMachine`

##### context

[`TouchContext`](../interfaces/TouchContext.md)

##### payload

[`TouchEventPayload`](../type-aliases/TouchEventPayload.md)

#### Returns

[`TouchStates`](../type-aliases/TouchStates.md)

***

### touchmove()

> **touchmove**(`stateMachine`, `context`, `payload`): [`TouchStates`](../type-aliases/TouchStates.md)

Defined in: [input-state-machine/touch-state-machine.ts:161](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/touch-state-machine.ts#L161)

#### Parameters

##### stateMachine

`TouchStateMachine`

##### context

[`TouchContext`](../interfaces/TouchContext.md)

##### payload

[`TouchEventPayload`](../type-aliases/TouchEventPayload.md)

#### Returns

[`TouchStates`](../type-aliases/TouchStates.md)

***

### uponEnter()

> **uponEnter**(`stateMachine`, `context`): `void`

Defined in: [being/interfaces.ts:119](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L119)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`TouchEventMapping`](../type-aliases/TouchEventMapping.md), [`TouchContext`](../interfaces/TouchContext.md), [`TouchStates`](../type-aliases/TouchStates.md)\>

##### context

[`TouchContext`](../interfaces/TouchContext.md)

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

[`StateMachine`](../interfaces/StateMachine.md)\<[`TouchEventMapping`](../type-aliases/TouchEventMapping.md), [`TouchContext`](../interfaces/TouchContext.md), [`TouchStates`](../type-aliases/TouchStates.md)\>

##### context

[`TouchContext`](../interfaces/TouchContext.md)

#### Returns

`void`

#### Inherited from

[`TemplateState`](TemplateState.md).[`uponLeave`](TemplateState.md#uponleave)
