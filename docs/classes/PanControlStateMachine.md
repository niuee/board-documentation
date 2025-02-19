[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / PanControlStateMachine

# Class: PanControlStateMachine

Defined in: [control-center/pan-control-state-machine.ts:34](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/pan-control-state-machine.ts#L34)

## Extends

- [`TemplateStateMachine`](TemplateStateMachine.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>

## Constructors

### new PanControlStateMachine()

> **new PanControlStateMachine**(`states`, `initialState`, `context`): [`PanControlStateMachine`](PanControlStateMachine.md)

Defined in: [control-center/pan-control-state-machine.ts:36](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/pan-control-state-machine.ts#L36)

#### Parameters

##### states

[`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<[`PanControlStates`](../type-aliases/PanControlStates.md), [`State`](../interfaces/State.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>\>

##### initialState

[`PanControlStates`](../type-aliases/PanControlStates.md)

##### context

[`PanContext`](../type-aliases/PanContext.md)

#### Returns

[`PanControlStateMachine`](PanControlStateMachine.md)

#### Overrides

[`TemplateStateMachine`](TemplateStateMachine.md).[`constructor`](TemplateStateMachine.md#constructors)

## Properties

### \_context

> `protected` **\_context**: [`PanContext`](../type-aliases/PanContext.md)

Defined in: [being/interfaces.ts:48](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L48)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_context`](TemplateStateMachine.md#_context)

***

### \_currentState

> `protected` **\_currentState**: [`PanControlStates`](../type-aliases/PanControlStates.md)

Defined in: [being/interfaces.ts:46](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L46)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_currentState`](TemplateStateMachine.md#_currentstate)

***

### \_happensCallbacks

> `protected` **\_happensCallbacks**: (`event`, `payload`, `context`) => `void`[]

Defined in: [being/interfaces.ts:51](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L51)

#### Parameters

##### event

keyof [`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md)

##### payload

\{\} | [`PanByInputEventPayload`](../type-aliases/PanByInputEventPayload.md) | [`PanToInputEventPayload`](../type-aliases/PanToInputEventPayload.md)

##### context

[`PanContext`](../type-aliases/PanContext.md)

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_happensCallbacks`](TemplateStateMachine.md#_happenscallbacks)

***

### \_stateChangeCallbacks

> `protected` **\_stateChangeCallbacks**: [`StateChangeCallback`](../type-aliases/StateChangeCallback.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>[]

Defined in: [being/interfaces.ts:50](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L50)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_stateChangeCallbacks`](TemplateStateMachine.md#_statechangecallbacks)

***

### \_states

> `protected` **\_states**: [`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<[`PanControlStates`](../type-aliases/PanControlStates.md), [`State`](../interfaces/State.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>\>

Defined in: [being/interfaces.ts:47](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L47)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_states`](TemplateStateMachine.md#_states)

***

### \_statesArray

> `protected` **\_statesArray**: [`PanControlStates`](../type-aliases/PanControlStates.md)[]

Defined in: [being/interfaces.ts:49](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L49)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_statesArray`](TemplateStateMachine.md#_statesarray)

## Accessors

### currentState

#### Get Signature

> **get** **currentState**(): `States`

Defined in: [being/interfaces.ts:85](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L85)

##### Returns

`States`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`currentState`](TemplateStateMachine.md#currentstate)

***

### limitEntireViewPort

#### Get Signature

> **get** **limitEntireViewPort**(): `boolean`

Defined in: [control-center/pan-control-state-machine.ts:56](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/pan-control-state-machine.ts#L56)

##### Returns

`boolean`

#### Set Signature

> **set** **limitEntireViewPort**(`limit`): `void`

Defined in: [control-center/pan-control-state-machine.ts:52](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/pan-control-state-machine.ts#L52)

##### Parameters

###### limit

`boolean`

##### Returns

`void`

***

### possibleStates

#### Get Signature

> **get** **possibleStates**(): `States`[]

Defined in: [being/interfaces.ts:93](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L93)

##### Returns

`States`[]

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`possibleStates`](TemplateStateMachine.md#possiblestates)

***

### states

#### Get Signature

> **get** **states**(): [`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<`States`, [`State`](../interfaces/State.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

Defined in: [being/interfaces.ts:97](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L97)

##### Returns

[`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<`States`, [`State`](../interfaces/State.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`states`](TemplateStateMachine.md#states-1)

## Methods

### happens()

> **happens**\<`K`\>(`event`, `payload`, `context`): [`PanControlStates`](../type-aliases/PanControlStates.md)

Defined in: [being/interfaces.ts:66](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L66)

#### Type Parameters

• **K** *extends* keyof [`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md)

#### Parameters

##### event

`K`

##### payload

[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md)\[`K`\]

##### context

[`PanContext`](../type-aliases/PanContext.md)

#### Returns

[`PanControlStates`](../type-aliases/PanControlStates.md)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`happens`](TemplateStateMachine.md#happens)

***

### initateTransition()

> **initateTransition**(): `void`

Defined in: [control-center/pan-control-state-machine.ts:48](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/pan-control-state-machine.ts#L48)

#### Returns

`void`

***

### notifyPanInput()

> **notifyPanInput**(`diff`): `void`

Defined in: [control-center/pan-control-state-machine.ts:40](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/pan-control-state-machine.ts#L40)

#### Parameters

##### diff

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### notifyPanToAnimationInput()

> **notifyPanToAnimationInput**(`target`): `void`

Defined in: [control-center/pan-control-state-machine.ts:44](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/control-center/pan-control-state-machine.ts#L44)

#### Parameters

##### target

[`Point`](../type-aliases/Point.md)

#### Returns

`void`

***

### onHappens()

> **onHappens**(`callback`): `void`

Defined in: [being/interfaces.ts:81](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L81)

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

Defined in: [being/interfaces.ts:77](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L77)

#### Parameters

##### callback

[`StateChangeCallback`](../type-aliases/StateChangeCallback.md)\<[`PanEventPayloadMapping`](../type-aliases/PanEventPayloadMapping.md), [`PanContext`](../type-aliases/PanContext.md), [`PanControlStates`](../type-aliases/PanControlStates.md)\>

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`onStateChange`](TemplateStateMachine.md#onstatechange)

***

### setContext()

> **setContext**(`context`): `void`

Defined in: [being/interfaces.ts:89](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L89)

#### Parameters

##### context

[`PanContext`](../type-aliases/PanContext.md)

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`setContext`](TemplateStateMachine.md#setcontext)

***

### switchTo()

> **switchTo**(`state`): `void`

Defined in: [being/interfaces.ts:62](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L62)

#### Parameters

##### state

[`PanControlStates`](../type-aliases/PanControlStates.md)

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`switchTo`](TemplateStateMachine.md#switchto)
