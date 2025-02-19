[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / TemplateState

# Class: `abstract` TemplateState\<EventPayloadMapping, Context, States\>

Defined in: [being/interfaces.ts:105](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L105)

## Extended by

- [`AcceptingUserInputState`](AcceptingUserInputState.md)
- [`TransitionState`](TransitionState.md)
- [`LockedOnObjectState`](LockedOnObjectState.md)
- [`ZoomAcceptingUserInputState`](ZoomAcceptingUserInputState.md)
- [`ZoomTransitionState`](ZoomTransitionState.md)
- [`ZoomLockedOnObjectState`](ZoomLockedOnObjectState.md)
- [`BoardIdleState`](BoardIdleState.md)
- [`ReadyToSelectState`](ReadyToSelectState.md)
- [`SelectingState`](SelectingState.md)
- [`ReadyToPanViaSpaceBarState`](ReadyToPanViaSpaceBarState.md)
- [`InitialPanState`](InitialPanState.md)
- [`ReadyToPanViaScrollWheelState`](ReadyToPanViaScrollWheelState.md)
- [`PanState`](PanState.md)
- [`PanViaScrollWheelState`](PanViaScrollWheelState.md)
- [`IdleState`](IdleState.md)
- [`PendingState`](PendingState.md)
- [`InProgressState`](InProgressState.md)

## Type Parameters

• **EventPayloadMapping**

• **Context**

• **States** *extends* `string` = `"IDLE"`

## Implements

- [`State`](../interfaces/State.md)\<`EventPayloadMapping`, `Context`, `States`\>

## Constructors

### new TemplateState()

> **new TemplateState**\<`EventPayloadMapping`, `Context`, `States`\>(): [`TemplateState`](TemplateState.md)\<`EventPayloadMapping`, `Context`, `States`\>

#### Returns

[`TemplateState`](TemplateState.md)\<`EventPayloadMapping`, `Context`, `States`\>

## Properties

### \_eventGuards

> `protected` **\_eventGuards**: [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<`EventPayloadMapping`, `States`, `Context`, [`Guard`](../type-aliases/Guard.md)\<`Context`, `string`\>\>\> = `{}`

Defined in: [being/interfaces.ts:109](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L109)

***

### \_guards

> `protected` **\_guards**: [`Guard`](../type-aliases/Guard.md)\<`Context`\> = `{}`

Defined in: [being/interfaces.ts:108](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L108)

***

### eventReactions

> `abstract` **eventReactions**: [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventAction`](../type-aliases/EventAction.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

Defined in: [being/interfaces.ts:107](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L107)

#### Implementation of

[`State`](../interfaces/State.md).[`eventReactions`](../interfaces/State.md#eventreactions)

## Accessors

### eventGuards

#### Get Signature

> **get** **eventGuards**(): [`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<`EventPayloadMapping`, `States`, `Context`, [`Guard`](../type-aliases/Guard.md)\<`Context`, `string`\>\>\>

Defined in: [being/interfaces.ts:115](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L115)

##### Returns

[`Partial`](https://www.typescriptlang.org/docs/handbook/utility-types.html#partialtype)\<[`EventGuards`](../type-aliases/EventGuards.md)\<`EventPayloadMapping`, `States`, `Context`, [`Guard`](../type-aliases/Guard.md)\<`Context`, `string`\>\>\>

#### Implementation of

[`State`](../interfaces/State.md).[`eventGuards`](../interfaces/State.md#eventguards)

***

### guards

#### Get Signature

> **get** **guards**(): [`Guard`](../type-aliases/Guard.md)\<`Context`\>

Defined in: [being/interfaces.ts:111](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L111)

##### Returns

[`Guard`](../type-aliases/Guard.md)\<`Context`\>

#### Implementation of

[`State`](../interfaces/State.md).[`guards`](../interfaces/State.md#guards)

## Methods

### handles()

> **handles**\<`K`\>(`stateMachine`, `event`, `payload`, `context`): `States`

Defined in: [being/interfaces.ts:127](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L127)

#### Type Parameters

• **K** *extends* `string` \| `number` \| `symbol`

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<`EventPayloadMapping`, `Context`, `States`\>

##### event

`K`

##### payload

`EventPayloadMapping`\[`K`\]

##### context

`Context`

#### Returns

`States`

#### Implementation of

[`State`](../interfaces/State.md).[`handles`](../interfaces/State.md#handles)

***

### uponEnter()

> **uponEnter**(`stateMachine`, `context`): `void`

Defined in: [being/interfaces.ts:119](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L119)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<`EventPayloadMapping`, `Context`, `States`\>

##### context

`Context`

#### Returns

`void`

#### Implementation of

[`State`](../interfaces/State.md).[`uponEnter`](../interfaces/State.md#uponenter)

***

### uponLeave()

> **uponLeave**(`stateMachine`, `context`): `void`

Defined in: [being/interfaces.ts:123](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L123)

#### Parameters

##### stateMachine

[`StateMachine`](../interfaces/StateMachine.md)\<`EventPayloadMapping`, `Context`, `States`\>

##### context

`Context`

#### Returns

`void`

#### Implementation of

[`State`](../interfaces/State.md).[`uponLeave`](../interfaces/State.md#uponleave)
