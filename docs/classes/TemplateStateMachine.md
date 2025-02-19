[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / TemplateStateMachine

# Class: `abstract` TemplateStateMachine\<EventPayloadMapping, Context, States\>

Defined in: [being/interfaces.ts:44](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L44)

## Extended by

- [`PanControlStateMachine`](PanControlStateMachine.md)
- [`ZoomControlStateMachine`](ZoomControlStateMachine.md)
- [`UserInputStateMachine`](UserInputStateMachine.md)
- [`TouchSM`](TouchSM.md)

## Type Parameters

• **EventPayloadMapping**

• **Context**

• **States** *extends* `string` = `"IDLE"`

## Implements

- [`StateMachine`](../interfaces/StateMachine.md)\<`EventPayloadMapping`, `Context`, `States`\>

## Constructors

### new TemplateStateMachine()

> **new TemplateStateMachine**\<`EventPayloadMapping`, `Context`, `States`\>(`states`, `initialState`, `context`): [`TemplateStateMachine`](TemplateStateMachine.md)\<`EventPayloadMapping`, `Context`, `States`\>

Defined in: [being/interfaces.ts:53](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L53)

#### Parameters

##### states

[`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<`States`, [`State`](../interfaces/State.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

##### initialState

`States`

##### context

`Context`

#### Returns

[`TemplateStateMachine`](TemplateStateMachine.md)\<`EventPayloadMapping`, `Context`, `States`\>

## Properties

### \_context

> `protected` **\_context**: `Context`

Defined in: [being/interfaces.ts:48](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L48)

***

### \_currentState

> `protected` **\_currentState**: `States`

Defined in: [being/interfaces.ts:46](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L46)

***

### \_happensCallbacks

> `protected` **\_happensCallbacks**: (`event`, `payload`, `context`) => `void`[]

Defined in: [being/interfaces.ts:51](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L51)

#### Parameters

##### event

keyof `EventPayloadMapping`

##### payload

`EventPayloadMapping`\[keyof `EventPayloadMapping`\]

##### context

`Context`

#### Returns

`void`

***

### \_stateChangeCallbacks

> `protected` **\_stateChangeCallbacks**: [`StateChangeCallback`](../type-aliases/StateChangeCallback.md)\<`EventPayloadMapping`, `Context`, `States`\>[]

Defined in: [being/interfaces.ts:50](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L50)

***

### \_states

> `protected` **\_states**: [`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<`States`, [`State`](../interfaces/State.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

Defined in: [being/interfaces.ts:47](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L47)

***

### \_statesArray

> `protected` **\_statesArray**: `States`[]

Defined in: [being/interfaces.ts:49](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L49)

## Accessors

### currentState

#### Get Signature

> **get** **currentState**(): `States`

Defined in: [being/interfaces.ts:85](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L85)

##### Returns

`States`

***

### possibleStates

#### Get Signature

> **get** **possibleStates**(): `States`[]

Defined in: [being/interfaces.ts:93](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L93)

##### Returns

`States`[]

#### Implementation of

[`StateMachine`](../interfaces/StateMachine.md).[`possibleStates`](../interfaces/StateMachine.md#possiblestates)

***

### states

#### Get Signature

> **get** **states**(): [`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<`States`, [`State`](../interfaces/State.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

Defined in: [being/interfaces.ts:97](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L97)

##### Returns

[`Record`](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)\<`States`, [`State`](../interfaces/State.md)\<`EventPayloadMapping`, `Context`, `States`\>\>

#### Implementation of

[`StateMachine`](../interfaces/StateMachine.md).[`states`](../interfaces/StateMachine.md#states)

## Methods

### happens()

> **happens**\<`K`\>(`event`, `payload`, `context`): `States`

Defined in: [being/interfaces.ts:66](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L66)

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

#### Implementation of

[`StateMachine`](../interfaces/StateMachine.md).[`happens`](../interfaces/StateMachine.md#happens)

***

### onHappens()

> **onHappens**(`callback`): `void`

Defined in: [being/interfaces.ts:81](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L81)

#### Parameters

##### callback

(`event`, `payload`, `context`) => `void`

#### Returns

`void`

#### Implementation of

[`StateMachine`](../interfaces/StateMachine.md).[`onHappens`](../interfaces/StateMachine.md#onhappens)

***

### onStateChange()

> **onStateChange**(`callback`): `void`

Defined in: [being/interfaces.ts:77](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L77)

#### Parameters

##### callback

[`StateChangeCallback`](../type-aliases/StateChangeCallback.md)\<`EventPayloadMapping`, `Context`, `States`\>

#### Returns

`void`

#### Implementation of

[`StateMachine`](../interfaces/StateMachine.md).[`onStateChange`](../interfaces/StateMachine.md#onstatechange)

***

### setContext()

> **setContext**(`context`): `void`

Defined in: [being/interfaces.ts:89](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L89)

#### Parameters

##### context

`Context`

#### Returns

`void`

#### Implementation of

[`StateMachine`](../interfaces/StateMachine.md).[`setContext`](../interfaces/StateMachine.md#setcontext)

***

### switchTo()

> **switchTo**(`state`): `void`

Defined in: [being/interfaces.ts:62](https://github.com/niuee/board/blob/cc09a87e934160adef876c4e11d51fd97e78653d/src/being/interfaces.ts#L62)

#### Parameters

##### state

`States`

#### Returns

`void`

#### Implementation of

[`StateMachine`](../interfaces/StateMachine.md).[`switchTo`](../interfaces/StateMachine.md#switchto)
