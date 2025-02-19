[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / ZoomAcceptingUserInputState

# Class: ZoomAcceptingUserInputState

Defined in: [control-center/zoom-control-state-machine.ts:49](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/zoom-control-state-machine.ts#L49)

## Extends

- [`TemplateState`](TemplateState.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>

## Constructors

### new ZoomAcceptingUserInputState()

> **new ZoomAcceptingUserInputState**(): [`ZoomAcceptingUserInputState`](ZoomAcceptingUserInputState.md)

#### Returns

[`ZoomAcceptingUserInputState`](ZoomAcceptingUserInputState.md)

#### Inherited from

[`TemplateState`](TemplateState.md).[`constructor`](TemplateState.md#constructors)

## Properties

### \_eventGuards

> `protected` **\_eventGuards**: [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`Guard`](../type-aliases/Guard.md)\<[`ZoomContext`](../type-aliases/ZoomContext.md), `string`\>\>\> = `{}`

Defined in: [being/interfaces.ts:109](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L109)

#### Inherited from

[`TemplateState`](TemplateState.md).[`_eventGuards`](TemplateState.md#_eventguards)

***

### \_guards

> `protected` **\_guards**: [`Guard`](../type-aliases/Guard.md)\<[`ZoomContext`](../type-aliases/ZoomContext.md)\> = `{}`

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

> **get** **eventReactions**(): [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventAction`](../type-aliases/EventAction.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>\>

Defined in: [control-center/zoom-control-state-machine.ts:57](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/zoom-control-state-machine.ts#L57)

##### Returns

[`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventAction`](../type-aliases/EventAction.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>\>

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

> **handles**\<`K`\>(`stateMachine`, `event`, `payload`, `context`): [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)

Defined in: [being/interfaces.ts:127](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L127)

#### Type Parameters

• **K** *extends* keyof [`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>

##### event

`K`

##### payload

[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md)\[`K`\]

##### context

[`ZoomContext`](../type-aliases/ZoomContext.md)

#### Returns

[`ZoomControlStates`](../type-aliases/ZoomControlStates.md)

#### Inherited from

[`TemplateState`](TemplateState.md).[`handles`](TemplateState.md#handles)

***

### initiateTransition()

> **initiateTransition**(`stateMachine`, `context`, `payload`): [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)

Defined in: [control-center/zoom-control-state-machine.ts:71](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/zoom-control-state-machine.ts#L71)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>

##### context

[`ZoomContext`](../type-aliases/ZoomContext.md)

##### payload

#### Returns

[`ZoomControlStates`](../type-aliases/ZoomControlStates.md)

***

### uponEnter()

> **uponEnter**(`stateMachine`, `context`): `void`

Defined in: [being/interfaces.ts:119](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L119)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>

##### context

[`ZoomContext`](../type-aliases/ZoomContext.md)

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

[`StateMachine`](../interfaces/StateMachine.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>

##### context

[`ZoomContext`](../type-aliases/ZoomContext.md)

#### Returns

`void`

#### Inherited from

[`TemplateState`](TemplateState.md).[`uponLeave`](TemplateState.md#uponleave)

***

### userZoomByAtInput()

> **userZoomByAtInput**(`stateMachine`, `context`, `payload`): [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)

Defined in: [control-center/zoom-control-state-machine.ts:61](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/zoom-control-state-machine.ts#L61)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>

##### context

[`ZoomContext`](../type-aliases/ZoomContext.md)

##### payload

[`ZoomByAtInputPayload`](../type-aliases/ZoomByAtInputPayload.md)

#### Returns

[`ZoomControlStates`](../type-aliases/ZoomControlStates.md)

***

### userZoomToAtInput()

> **userZoomToAtInput**(`stateMachine`, `context`, `payload`): [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)

Defined in: [control-center/zoom-control-state-machine.ts:66](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/zoom-control-state-machine.ts#L66)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>

##### context

[`ZoomContext`](../type-aliases/ZoomContext.md)

##### payload

[`ZoomToAtInputPayload`](../type-aliases/ZoomToAtInputPayload.md)

#### Returns

[`ZoomControlStates`](../type-aliases/ZoomControlStates.md)
