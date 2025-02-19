[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / UserInputStateMachine

# Class: UserInputStateMachine\<EventPayloadMapping, Context, States\>

Defined in: [input-state-machine/input-state-machine.ts:439](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/input-state-machine/input-state-machine.ts#L439)

## Extends

- [`TemplateStateMachine`](TemplateStateMachine.md)\<`EventPayloadMapping`, `Context`, `States`\>

## Type Parameters

• **EventPayloadMapping**

• **Context**

• **States** *extends* `string` = `"IDLE"`

## Constructors

### new UserInputStateMachine()

> **new UserInputStateMachine**\<`EventPayloadMapping`, `Context`, `States`\>(`states`, `initialState`, `context`): [`UserInputStateMachine`](UserInputStateMachine.md)\<`EventPayloadMapping`, `Context`, `States`\>

Defined in: [input-state-machine/input-state-machine.ts:442](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/input-state-machine/input-state-machine.ts#L442)

#### Parameters

##### states

[`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<`States`, [`State`](../interfaces/State.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

##### initialState

`States`

##### context

`Context`

#### Returns

[`UserInputStateMachine`](UserInputStateMachine.md)\<`EventPayloadMapping`, `Context`, `States`\>

#### Overrides

[`TemplateStateMachine`](TemplateStateMachine.md).[`constructor`](TemplateStateMachine.md#constructors)

## Properties

### \_context

> `protected` **\_context**: `Context`

Defined in: [being/interfaces.ts:48](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L48)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_context`](TemplateStateMachine.md#_context)

***

### \_currentState

> `protected` **\_currentState**: `States`

Defined in: [being/interfaces.ts:46](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L46)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_currentState`](TemplateStateMachine.md#_currentstate)

***

### \_happensCallbacks

> `protected` **\_happensCallbacks**: (`event`, `payload`, `context`) => `void`[]

Defined in: [being/interfaces.ts:51](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L51)

#### Parameters

##### event

keyof `EventPayloadMapping`

##### payload

`EventPayloadMapping`\[keyof `EventPayloadMapping`\]

##### context

`Context`

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_happensCallbacks`](TemplateStateMachine.md#_happenscallbacks)

***

### \_stateChangeCallbacks

> `protected` **\_stateChangeCallbacks**: [`StateChangeCallback`](../type-aliases/StateChangeCallback.md)\<`EventPayloadMapping`, `Context`, `States`\>[]

Defined in: [being/interfaces.ts:50](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L50)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_stateChangeCallbacks`](TemplateStateMachine.md#_statechangecallbacks)

***

### \_states

> `protected` **\_states**: [`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<`States`, [`State`](../interfaces/State.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

Defined in: [being/interfaces.ts:47](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L47)

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`_states`](TemplateStateMachine.md#_states)

***

### \_statesArray

> `protected` **\_statesArray**: `States`[]

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

Defined in: [input-state-machine/input-state-machine.ts:450](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/input-state-machine/input-state-machine.ts#L450)

##### Returns

`States`[]

#### Overrides

[`TemplateStateMachine`](TemplateStateMachine.md).[`possibleStates`](TemplateStateMachine.md#possiblestates)

***

### states

#### Get Signature

> **get** **states**(): [`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<`States`, [`State`](../interfaces/State.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

Defined in: [input-state-machine/input-state-machine.ts:454](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/input-state-machine/input-state-machine.ts#L454)

##### Returns

[`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<`States`, [`State`](../interfaces/State.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

#### Overrides

[`TemplateStateMachine`](TemplateStateMachine.md).[`states`](TemplateStateMachine.md#states-1)

## Methods

### happens()

> **happens**\<`K`\>(`event`, `payload`, `context`): `States`

Defined in: [being/interfaces.ts:66](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L66)

#### Type Parameters

• **K** *extends* `string` \| `number` \| `symbol`

#### Parameters

##### event

`K`

##### payload

`EventPayloadMapping`\[`K`\]

##### context

`Context`

#### Returns

`States`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`happens`](TemplateStateMachine.md#happens)

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

[`StateChangeCallback`](../type-aliases/StateChangeCallback.md)\<`EventPayloadMapping`, `Context`, `States`\>

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`onStateChange`](TemplateStateMachine.md#onstatechange)

***

### setContext()

> **setContext**(`context`): `void`

Defined in: [input-state-machine/input-state-machine.ts:446](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/input-state-machine/input-state-machine.ts#L446)

#### Parameters

##### context

`Context`

#### Returns

`void`

#### Overrides

[`TemplateStateMachine`](TemplateStateMachine.md).[`setContext`](TemplateStateMachine.md#setcontext)

***

### switchTo()

> **switchTo**(`state`): `void`

Defined in: [being/interfaces.ts:62](https://github.com/niuee/board/blob/d74620e4e63da3004adfc7105b7f1136fce9577c/src/being/interfaces.ts#L62)

#### Parameters

##### state

`States`

#### Returns

`void`

#### Inherited from

[`TemplateStateMachine`](TemplateStateMachine.md).[`switchTo`](TemplateStateMachine.md#switchto)
