[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / TransitionState

# Class: TransitionState

Defined in: [control-center/pan-control-state-machine.ts:101](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/pan-control-state-machine.ts#L101)

## Extends

- [`TemplateState`](TemplateState.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>

## Constructors

### new TransitionState()

> **new TransitionState**(): [`TransitionState`](TransitionState.md)

Defined in: [control-center/pan-control-state-machine.ts:103](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/pan-control-state-machine.ts#L103)

#### Returns

[`TransitionState`](TransitionState.md)

#### Overrides

[`TemplateState`](TemplateState.md).[`constructor`](TemplateState.md#constructors)

## Properties

### \_eventGuards

> `protected` **\_eventGuards**: [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanControlStates`](../type-aliases/PanControlStates.md), [`PanContext`](../type-aliases/PanContext.md), [`Guard`](../type-aliases/Guard.md)\<[`PanContext`](../type-aliases/PanContext.md), `string`\>\>\> = `{}`

Defined in: [being/interfaces.ts:109](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L109)

#### Inherited from

[`TemplateState`](TemplateState.md).[`_eventGuards`](TemplateState.md#_eventguards)

***

### \_guards

> `protected` **\_guards**: [`Guard`](../type-aliases/Guard.md)\<[`PanContext`](../type-aliases/PanContext.md)\> = `{}`

Defined in: [being/interfaces.ts:108](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L108)

#### Inherited from

[`TemplateState`](TemplateState.md).[`_guards`](TemplateState.md#_guards)

***

### eventReactions

> **eventReactions**: [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventAction`](../type-aliases/EventAction.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>\>

Defined in: [control-center/pan-control-state-machine.ts:107](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/pan-control-state-machine.ts#L107)

#### Overrides

[`TemplateState`](TemplateState.md).[`eventReactions`](TemplateState.md#eventreactions)

## Accessors

### eventGuards

#### Get Signature

> **get** **eventGuards**(): [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<`EventPayloadMapping`, `States`, `Context`, [`Guard`](../type-aliases/Guard.md)\<`Context`, `string`\>\>\>

Defined in: [being/interfaces.ts:115](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L115)

##### Returns

[`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<`EventPayloadMapping`, `States`, `Context`, [`Guard`](../type-aliases/Guard.md)\<`Context`, `string`\>\>\>

#### Inherited from

[`TemplateState`](TemplateState.md).[`eventGuards`](TemplateState.md#eventguards)

***

### guards

#### Get Signature

> **get** **guards**(): [`Guard`](../type-aliases/Guard.md)\<`Context`\>

Defined in: [being/interfaces.ts:111](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L111)

##### Returns

[`Guard`](../type-aliases/Guard.md)\<`Context`\>

#### Inherited from

[`TemplateState`](TemplateState.md).[`guards`](TemplateState.md#guards)

## Methods

### handles()

> **handles**\<`K`\>(`stateMachine`, `event`, `payload`, `context`): [`PanControlStates`](../type-aliases/PanControlStates.md)

Defined in: [being/interfaces.ts:127](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L127)

#### Type Parameters

• **K** *extends* keyof [`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>

##### event

`K`

##### payload

[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md)\[`K`\]

##### context

[`PanContext`](../type-aliases/PanContext.md)

#### Returns

[`PanControlStates`](../type-aliases/PanControlStates.md)

#### Inherited from

[`TemplateState`](TemplateState.md).[`handles`](TemplateState.md#handles)

***

### lockedOnObjectPanByInputHandler()

> **lockedOnObjectPanByInputHandler**(`stateMachine`, `context`, `payload`): [`PanControlStates`](../type-aliases/PanControlStates.md)

Defined in: [control-center/pan-control-state-machine.ts:136](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/pan-control-state-machine.ts#L136)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>

##### context

[`PanContext`](../type-aliases/PanContext.md)

##### payload

[`PanByInputEventPayload`](../type-aliases/PanByInputEventPayload.md)

#### Returns

[`PanControlStates`](../type-aliases/PanControlStates.md)

***

### lockedOnObjectPanToInputHandler()

> **lockedOnObjectPanToInputHandler**(`stateMachine`, `context`, `payload`): [`PanControlStates`](../type-aliases/PanControlStates.md)

Defined in: [control-center/pan-control-state-machine.ts:141](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/pan-control-state-machine.ts#L141)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>

##### context

[`PanContext`](../type-aliases/PanContext.md)

##### payload

[`PanToInputEventPayload`](../type-aliases/PanToInputEventPayload.md)

#### Returns

[`PanControlStates`](../type-aliases/PanControlStates.md)

***

### transitionPanByInputHandler()

> **transitionPanByInputHandler**(`stateMachine`, `context`, `payload`): [`PanControlStates`](../type-aliases/PanControlStates.md)

Defined in: [control-center/pan-control-state-machine.ts:126](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/pan-control-state-machine.ts#L126)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>

##### context

[`PanContext`](../type-aliases/PanContext.md)

##### payload

[`PanByInputEventPayload`](../type-aliases/PanByInputEventPayload.md)

#### Returns

[`PanControlStates`](../type-aliases/PanControlStates.md)

***

### transitionPanToInputHandler()

> **transitionPanToInputHandler**(`stateMachine`, `context`, `payload`): [`PanControlStates`](../type-aliases/PanControlStates.md)

Defined in: [control-center/pan-control-state-machine.ts:131](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/pan-control-state-machine.ts#L131)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>

##### context

[`PanContext`](../type-aliases/PanContext.md)

##### payload

[`PanToInputEventPayload`](../type-aliases/PanToInputEventPayload.md)

#### Returns

[`PanControlStates`](../type-aliases/PanControlStates.md)

***

### uponEnter()

> **uponEnter**(`stateMachine`, `context`): `void`

Defined in: [being/interfaces.ts:119](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L119)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>

##### context

[`PanContext`](../type-aliases/PanContext.md)

#### Returns

`void`

#### Inherited from

[`TemplateState`](TemplateState.md).[`uponEnter`](TemplateState.md#uponenter)

***

### uponLeave()

> **uponLeave**(`stateMachine`, `context`): `void`

Defined in: [being/interfaces.ts:123](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L123)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>

##### context

[`PanContext`](../type-aliases/PanContext.md)

#### Returns

`void`

#### Inherited from

[`TemplateState`](TemplateState.md).[`uponLeave`](TemplateState.md#uponleave)

***

### userPanByInputHandler()

> **userPanByInputHandler**(`stateMachine`, `context`, `payload`): [`PanControlStates`](../type-aliases/PanControlStates.md)

Defined in: [control-center/pan-control-state-machine.ts:116](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/pan-control-state-machine.ts#L116)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>

##### context

[`PanContext`](../type-aliases/PanContext.md)

##### payload

[`PanByInputEventPayload`](../type-aliases/PanByInputEventPayload.md)

#### Returns

[`PanControlStates`](../type-aliases/PanControlStates.md)

***

### userPanToInputHandler()

> **userPanToInputHandler**(`stateMachine`, `context`, `payload`): [`PanControlStates`](../type-aliases/PanControlStates.md)

Defined in: [control-center/pan-control-state-machine.ts:121](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/control-center/pan-control-state-machine.ts#L121)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>

##### context

[`PanContext`](../type-aliases/PanContext.md)

##### payload

[`PanToInputEventPayload`](../type-aliases/PanToInputEventPayload.md)

#### Returns

[`PanControlStates`](../type-aliases/PanControlStates.md)
