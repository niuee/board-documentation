[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / TouchSM

# Class: TouchSM

Defined in: [input-state-machine/touch-state-machine.ts:193](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/touch-state-machine.ts#L193)

## Extends

- [`TemplateStateMachine`](TemplateStateMachine.md)\<[`TouchEventMapping`](../type-aliases/TouchEventMapping.md), [`TouchContext`](../interfaces/TouchContext.md), [`TouchStates`](../type-aliases/TouchStates.md)\>

## Constructors

### new TouchSM()

> **new TouchSM**(`context`): [`TouchSM`](TouchSM.md)

Defined in: [input-state-machine/touch-state-machine.ts:195](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/input-state-machine/touch-state-machine.ts#L195)

#### Parameters

##### context

[`TouchContext`](../interfaces/TouchContext.md)

#### Returns

[`TouchSM`](TouchSM.md)

#### Overrides

[`TemplateStateMachine`](TemplateStateMachine.md).[`constructor`](TemplateStateMachine.md#constructors)

## Properties

### \_context

> `protected` **\_context**: [`TouchContext`](../interfaces/TouchContext.md)

Defined in: [being/interfaces.ts:48](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L48)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_context`](TemplateStateMachine.md#_context)

***

### \_currentState

> `protected` **\_currentState**: [`TouchStates`](../type-aliases/TouchStates.md)

Defined in: [being/interfaces.ts:46](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L46)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_currentState`](TemplateStateMachine.md#_currentstate)

***

### \_happensCallbacks

> `protected` **\_happensCallbacks**: (`event`, `payload`, `context`) => `void`[]

Defined in: [being/interfaces.ts:51](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L51)

#### Parameters

##### event

keyof [`TouchEventMapping`](../type-aliases/TouchEventMapping.md)

##### payload

[`TouchEventPayload`](../type-aliases/TouchEventPayload.md)

##### context

[`TouchContext`](../interfaces/TouchContext.md)

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_happensCallbacks`](TemplateStateMachine.md#_happenscallbacks)

***

### \_stateChangeCallbacks

> `protected` **\_stateChangeCallbacks**: [`StateChangeCallback`](../type-aliases/StateChangeCallback.md)\<[`TouchEventMapping`](../type-aliases/TouchEventMapping.md), [`TouchContext`](../interfaces/TouchContext.md), [`TouchStates`](../type-aliases/TouchStates.md)\>[]

Defined in: [being/interfaces.ts:50](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L50)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_stateChangeCallbacks`](TemplateStateMachine.md#_statechangecallbacks)

***

### \_states

> `protected` **\_states**: [`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<[`TouchStates`](../type-aliases/TouchStates.md), [`State`](../interfaces/State.md)\<[`TouchEventMapping`](../type-aliases/TouchEventMapping.md), [`TouchContext`](../interfaces/TouchContext.md), [`TouchStates`](../type-aliases/TouchStates.md)\>\>

Defined in: [being/interfaces.ts:47](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L47)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_states`](TemplateStateMachine.md#_states)

***

### \_statesArray

> `protected` **\_statesArray**: [`TouchStates`](../type-aliases/TouchStates.md)[]

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

> **happens**\<`K`\>(`event`, `payload`, `context`): [`TouchStates`](../type-aliases/TouchStates.md)

Defined in: [being/interfaces.ts:66](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L66)

#### Type Parameters

• **K** *extends* keyof [`TouchEventMapping`](../type-aliases/TouchEventMapping.md)

#### Parameters

##### event

`K`

##### payload

[`TouchEventMapping`](../type-aliases/TouchEventMapping.md)\[`K`\]

##### context

[`TouchContext`](../interfaces/TouchContext.md)

#### Returns

[`TouchStates`](../type-aliases/TouchStates.md)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`happens`](TemplateStateMachine.md#happens)

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

[`StateChangeCallback`](../type-aliases/StateChangeCallback.md)\<[`TouchEventMapping`](../type-aliases/TouchEventMapping.md), [`TouchContext`](../interfaces/TouchContext.md), [`TouchStates`](../type-aliases/TouchStates.md)\>

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

[`TouchContext`](../interfaces/TouchContext.md)

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

[`TouchStates`](../type-aliases/TouchStates.md)

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`switchTo`](TemplateStateMachine.md#switchto)
