[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / ZoomControlStateMachine

# Class: ZoomControlStateMachine

Defined in: [control-center/zoom-control-state-machine.ts:177](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/zoom-control-state-machine.ts#L177)

## Extends

- [`TemplateStateMachine`](TemplateStateMachine.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>

## Constructors

### new ZoomControlStateMachine()

> **new ZoomControlStateMachine**(`states`, `initialState`, `context`): [`ZoomControlStateMachine`](ZoomControlStateMachine.md)

Defined in: [control-center/zoom-control-state-machine.ts:179](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/zoom-control-state-machine.ts#L179)

#### Parameters

##### states

[`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<[`ZoomControlStates`](../type-aliases/ZoomControlStates.md), [`State`](../interfaces/State.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>\>

##### initialState

[`ZoomControlStates`](../type-aliases/ZoomControlStates.md)

##### context

[`ZoomContext`](../type-aliases/ZoomContext.md)

#### Returns

[`ZoomControlStateMachine`](ZoomControlStateMachine.md)

#### Overrides

[`TemplateStateMachine`](TemplateStateMachine.md).[`constructor`](TemplateStateMachine.md#constructors)

## Properties

### \_context

> `protected` **\_context**: [`ZoomContext`](../type-aliases/ZoomContext.md)

Defined in: [being/interfaces.ts:48](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L48)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_context`](TemplateStateMachine.md#_context)

***

### \_currentState

> `protected` **\_currentState**: [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)

Defined in: [being/interfaces.ts:46](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L46)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_currentState`](TemplateStateMachine.md#_currentstate)

***

### \_happensCallbacks

> `protected` **\_happensCallbacks**: (`event`, `payload`, `context`) => `void`[]

Defined in: [being/interfaces.ts:51](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L51)

#### Parameters

##### event

keyof [`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md)

##### payload

\{\} | [`ZoomByAtInputPayload`](../type-aliases/ZoomByAtInputPayload.md) | [`ZoomToAtInputPayload`](../type-aliases/ZoomToAtInputPayload.md) | [`ZoomByPayload`](../type-aliases/ZoomByPayload.md)

##### context

[`ZoomContext`](../type-aliases/ZoomContext.md)

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_happensCallbacks`](TemplateStateMachine.md#_happenscallbacks)

***

### \_stateChangeCallbacks

> `protected` **\_stateChangeCallbacks**: [`StateChangeCallback`](../type-aliases/StateChangeCallback.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>[]

Defined in: [being/interfaces.ts:50](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L50)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_stateChangeCallbacks`](TemplateStateMachine.md#_statechangecallbacks)

***

### \_states

> `protected` **\_states**: [`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<[`ZoomControlStates`](../type-aliases/ZoomControlStates.md), [`State`](../interfaces/State.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>\>

Defined in: [being/interfaces.ts:47](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L47)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_states`](TemplateStateMachine.md#_states)

***

### \_statesArray

> `protected` **\_statesArray**: [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)[]

Defined in: [being/interfaces.ts:49](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L49)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_statesArray`](TemplateStateMachine.md#_statesarray)

## Accessors

### currentState

#### Get Signature

> **get** **currentState**(): `States`

Defined in: [being/interfaces.ts:85](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L85)

##### Returns

`States`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`currentState`](TemplateStateMachine.md#currentstate)

***

### possibleStates

#### Get Signature

> **get** **possibleStates**(): `States`[]

Defined in: [being/interfaces.ts:93](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L93)

##### Returns

`States`[]

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`possibleStates`](TemplateStateMachine.md#possiblestates)

***

### states

#### Get Signature

> **get** **states**(): [`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<`States`, [`State`](../interfaces/State.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

Defined in: [being/interfaces.ts:97](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L97)

##### Returns

[`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<`States`, [`State`](../interfaces/State.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`states`](TemplateStateMachine.md#states-1)

## Methods

### happens()

> **happens**\<`K`\>(`event`, `payload`, `context`): [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)

Defined in: [being/interfaces.ts:66](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L66)

#### Type Parameters

• **K** *extends* keyof [`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md)

#### Parameters

##### event

`K`

##### payload

[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md)\[`K`\]

##### context

[`ZoomContext`](../type-aliases/ZoomContext.md)

#### Returns

[`ZoomControlStates`](../type-aliases/ZoomControlStates.md)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`happens`](TemplateStateMachine.md#happens)

***

### initateTransition()

> **initateTransition**(): `void`

Defined in: [control-center/zoom-control-state-machine.ts:199](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/zoom-control-state-machine.ts#L199)

#### Returns

`void`

***

### notifyZoomByAtInput()

> **notifyZoomByAtInput**(`delta`, `at`): `void`

Defined in: [control-center/zoom-control-state-machine.ts:183](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/zoom-control-state-machine.ts#L183)

#### Parameters

##### delta

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### notifyZoomByAtInputAnimation()

> **notifyZoomByAtInputAnimation**(`delta`, `at`): `void`

Defined in: [control-center/zoom-control-state-machine.ts:187](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/zoom-control-state-machine.ts#L187)

#### Parameters

##### delta

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### notifyZoomToAtCenterInput()

> **notifyZoomToAtCenterInput**(`targetZoom`, `at`): `void`

Defined in: [control-center/zoom-control-state-machine.ts:191](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/zoom-control-state-machine.ts#L191)

#### Parameters

##### targetZoom

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### notifyZoomToAtWorldInput()

> **notifyZoomToAtWorldInput**(`targetZoom`, `at`): `void`

Defined in: [control-center/zoom-control-state-machine.ts:195](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/control-center/zoom-control-state-machine.ts#L195)

#### Parameters

##### targetZoom

`number`

##### at

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### onHappens()

> **onHappens**(`callback`): `void`

Defined in: [being/interfaces.ts:81](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L81)

#### Parameters

##### callback

(`event`, `payload`, `context`) => `void`

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`onHappens`](TemplateStateMachine.md#onhappens)

***

### onStateChange()

> **onStateChange**(`callback`): `void`

Defined in: [being/interfaces.ts:77](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L77)

#### Parameters

##### callback

[`StateChangeCallback`](../type-aliases/StateChangeCallback.md)\<[`ZoomEventPayloadMapping`](../type-aliases/ZoomEventPayloadMapping.md), [`ZoomContext`](../type-aliases/ZoomContext.md), [`ZoomControlStates`](../type-aliases/ZoomControlStates.md)\>

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`onStateChange`](TemplateStateMachine.md#onstatechange)

***

### setContext()

> **setContext**(`context`): `void`

Defined in: [being/interfaces.ts:89](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L89)

#### Parameters

##### context

[`ZoomContext`](../type-aliases/ZoomContext.md)

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`setContext`](TemplateStateMachine.md#setcontext)

***

### switchTo()

> **switchTo**(`state`): `void`

Defined in: [being/interfaces.ts:62](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L62)

#### Parameters

##### state

[`ZoomControlStates`](../type-aliases/ZoomControlStates.md)

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`switchTo`](TemplateStateMachine.md#switchto)
