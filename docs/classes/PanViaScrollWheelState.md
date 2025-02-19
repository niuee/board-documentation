[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / PanViaScrollWheelState

# Class: PanViaScrollWheelState

Defined in: [input-state-machine/input-state-machine.ts:396](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/input-state-machine.ts#L396)

## Extends

- [`TemplateState`](TemplateState.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

## Constructors

### new PanViaScrollWheelState()

> **new PanViaScrollWheelState**(): [`PanViaScrollWheelState`](PanViaScrollWheelState.md)

#### Returns

[`PanViaScrollWheelState`](PanViaScrollWheelState.md)

#### Inherited from

[`TemplateState`](TemplateState.md).[`constructor`](TemplateState.md#constructors)

## Properties

### \_eventGuards

> `protected` **\_eventGuards**: [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardStates`](../type-aliases/BoardStates.md), [`BoardContext`](../type-aliases/BoardContext.md), [`Guard`](../type-aliases/Guard.md)\<[`BoardContext`](../type-aliases/BoardContext.md), `string`\>\>\> = `{}`

Defined in: [being/interfaces.ts:109](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L109)

#### Inherited from

[`TemplateState`](TemplateState.md).[`_eventGuards`](TemplateState.md#_eventguards)

***

### \_guards

> `protected` **\_guards**: [`Guard`](../type-aliases/Guard.md)\<[`BoardContext`](../type-aliases/BoardContext.md)\> = `{}`

Defined in: [being/interfaces.ts:108](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L108)

#### Inherited from

[`TemplateState`](TemplateState.md).[`_guards`](TemplateState.md#_guards)

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

### eventReactions

#### Get Signature

> **get** **eventReactions**(): [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventAction`](../type-aliases/EventAction.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>\>

Defined in: [input-state-machine/input-state-machine.ts:409](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/input-state-machine.ts#L409)

##### Returns

[`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventAction`](../type-aliases/EventAction.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>\>

#### Overrides

[`TemplateState`](TemplateState.md).[`eventReactions`](TemplateState.md#eventreactions)

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

> **handles**\<`K`\>(`stateMachine`, `event`, `payload`, `context`): [`BoardStates`](../type-aliases/BoardStates.md)

Defined in: [being/interfaces.ts:127](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L127)

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

### middlePointerMoveHandler()

> **middlePointerMoveHandler**(`stateMachine`, `context`, `payload`): [`BoardStates`](../type-aliases/BoardStates.md)

Defined in: [input-state-machine/input-state-machine.ts:413](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/input-state-machine.ts#L413)

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

### middlePointerUpHandler()

> **middlePointerUpHandler**(`stateMachine`, `context`, `payload`): [`BoardStates`](../type-aliases/BoardStates.md)

Defined in: [input-state-machine/input-state-machine.ts:426](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/input-state-machine/input-state-machine.ts#L426)

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

Defined in: [being/interfaces.ts:119](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L119)

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

Defined in: [being/interfaces.ts:123](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/being/interfaces.ts#L123)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<[`BoardEventMapping`](../type-aliases/BoardEventMapping.md), [`BoardContext`](../type-aliases/BoardContext.md), [`BoardStates`](../type-aliases/BoardStates.md)\>

##### context

[`BoardContext`](../type-aliases/BoardContext.md)

#### Returns

`void`

#### Inherited from

[`TemplateState`](TemplateState.md).[`uponLeave`](TemplateState.md#uponleave)
