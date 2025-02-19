[**@niuee/board**](../README.md)

***

[@niuee/board](../globals.md) / Board

# Class: Board

Defined in: [boardify/board.ts:45](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L45)

## Translation Block

Usage
```typescript
import { Board } from "@niuee/board";

// however you prefer to get a canvas element that is already in the DOM
const canvasElement = document.querySelector("canvas") as HTMLCanvasElement;
const board = new Board(canvasElement);

const stepFn = board.getStepFunction(); 
const context = board.getContext();

function step(timestamp: number){
   stepFn(timestamp);
// do other stuff after the board has stepped
//.
//.
//.
}
```

## Translation Block

Alternatively you can import the board class as from a subdirectory; this shaves the bundle size a bit but not a lot though. As the board is the overall entry point for the library.

```typescript
import {Board} from "@niuee/board/boardify";
```

## Constructors

### new Board()

> **new Board**(`canvas`, `eventTarget`): [`Board`](Board.md)

Defined in: [boardify/board.ts:64](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L64)

#### Parameters

##### canvas

[`HTMLCanvasElement`](https://developer.mozilla.org/docs/Web/API/HTMLCanvasElement)

##### eventTarget

[`EventTargetWithPointerEvents`](../type-aliases/EventTargetWithPointerEvents.md) = `canvas`

#### Returns

[`Board`](Board.md)

## Accessors

### alignCoordinateSystem

#### Get Signature

> **get** **alignCoordinateSystem**(): `boolean`

Defined in: [boardify/board.ts:200](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L200)

##### Returns

`boolean`

#### Set Signature

> **set** **alignCoordinateSystem**(`align`): `void`

Defined in: [boardify/board.ts:194](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L194)

##### Translation Block

This is an attribute that determines if the coordinate system should be aligned with the one of the HTML canvas element. The default is true.

##### Parameters

###### align

`boolean`

##### Returns

`void`

***

### camera

#### Get Signature

> **get** **camera**(): [`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md)

Defined in: [boardify/board.ts:277](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L277)

##### Translation Block

The underlying camera of the board. The camera of the board can be switched.
The boundaries are based on camera. Meaning you can have camera with different boundaries, and you can switch between them during runtime.

##### Returns

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md)

#### Set Signature

> **set** **camera**(`camera`): `void`

Defined in: [boardify/board.ts:281](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L281)

##### Parameters

###### camera

[`ObservableBoardCamera`](../interfaces/ObservableBoardCamera.md)

##### Returns

`void`

***

### context

#### Get Signature

> **get** **context**(): [`CanvasRenderingContext2D`](https://developer.mozilla.org/docs/Web/API/CanvasRenderingContext2D)

Defined in: [boardify/board.ts:223](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L223)

##### Translation Block

The context used to draw stuff on the canvas.

##### Returns

[`CanvasRenderingContext2D`](https://developer.mozilla.org/docs/Web/API/CanvasRenderingContext2D)

***

### controlCenter

#### Get Signature

> **get** **controlCenter**(): [`InputControlCenter`](../interfaces/InputControlCenter.md)

Defined in: [boardify/board.ts:287](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L287)

##### Returns

[`InputControlCenter`](../interfaces/InputControlCenter.md)

***

### fullScreen

#### Get Signature

> **get** **fullScreen**(): `boolean`

Defined in: [boardify/board.ts:208](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L208)

##### Translation Block

Determines if the board should be full screen. If this is set to true, the width and height of the board will be set to the window's inner width and inner height respectively.
If set to true the width and height of the board will resize with the window.

##### Returns

`boolean`

#### Set Signature

> **set** **fullScreen**(`value`): `void`

Defined in: [boardify/board.ts:212](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L212)

##### Parameters

###### value

`boolean`

##### Returns

`void`

***

### height

#### Get Signature

> **get** **height**(): `number`

Defined in: [boardify/board.ts:187](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L187)

##### Returns

`number`

#### Set Signature

> **set** **height**(`height`): `void`

Defined in: [boardify/board.ts:175](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L175)

##### Translation Block

This is in sync with the canvas height and the camera view port height. This is not the board's height.
If the limitEntireViewPort is set to true, the min zoom level is updated based on the height.

##### Parameters

###### height

`number`

##### Returns

`void`

***

### kmtStrategy

#### Get Signature

> **get** **kmtStrategy**(): [`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md)

Defined in: [boardify/board.ts:255](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L255)

##### Returns

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md)

#### Set Signature

> **set** **kmtStrategy**(`strategy`): `void`

Defined in: [boardify/board.ts:249](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L249)

##### Translation Block

The strategy used to handle the keyboard, mouse events. The default strategy is the DefaultBoardKMTStrategy. 
You can implement your own strategy by implementing the BoardKMTStrategy interface.

##### Parameters

###### strategy

[`BoardKMTStrategy`](../interfaces/BoardKMTStrategy.md)

##### Returns

`void`

***

### limitEntireViewPort

#### Get Signature

> **get** **limitEntireViewPort**(): `boolean`

Defined in: [boardify/board.ts:241](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L241)

##### Returns

`boolean`

#### Set Signature

> **set** **limitEntireViewPort**(`value`): `void`

Defined in: [boardify/board.ts:231](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L231)

##### Translation Block

Determines the behavior of the camera when the camera is at the edge of the boundaries. If set to true, the entire view port would not move beyond the boundaries.
If set to false, only the center of the camera is bounded by the boundaries.

##### Parameters

###### value

`boolean`

##### Returns

`void`

***

### maxHalfTransHeight

#### Get Signature

> **get** **maxHalfTransHeight**(): `number`

Defined in: [boardify/board.ts:351](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L351)

##### Translation Block

The max translation height of the camera. This is the maximum distance the camera can move in the vertical direction.

##### Returns

`number`

***

### maxHalfTransWidth

#### Get Signature

> **get** **maxHalfTransWidth**(): `number`

Defined in: [boardify/board.ts:358](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L358)

##### Translation Block

The max translation width of the camera. This is the maximum distance the camera can move in the horizontal direction.

##### Returns

`number`

***

### selectionBox

#### Get Signature

> **get** **selectionBox**(): [`SelectionBox`](SelectionBox.md)

Defined in: [boardify/board.ts:410](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L410)

##### Returns

[`SelectionBox`](SelectionBox.md)

***

### touchStrategy

#### Get Signature

> **get** **touchStrategy**(): [`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md)

Defined in: [boardify/board.ts:269](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L269)

##### Returns

[`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md)

#### Set Signature

> **set** **touchStrategy**(`strategy`): `void`

Defined in: [boardify/board.ts:263](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L263)

##### Translation Block

The strategy used to handle touch events. The default strategy is the DefaultTouchStrategy.
You can implement your own strategy by implementing the BoardTouchStrategy interface.

##### Parameters

###### strategy

[`BoardTouchStrategy`](../interfaces/BoardTouchStrategy.md)

##### Returns

`void`

***

### width

#### Get Signature

> **get** **width**(): `number`

Defined in: [boardify/board.ts:167](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L167)

##### Returns

`number`

#### Set Signature

> **set** **width**(`width`): `void`

Defined in: [boardify/board.ts:155](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L155)

##### Translation Block

This is in sync with the canvas width and the camera view port width. This is not the board's width.
If the limitEntireViewPort is set to true, the min zoom level is updated based on the width of the canvas.

##### Parameters

###### width

`number`

##### Returns

`void`

## Methods

### convertWindowPoint2WorldCoord()

> **convertWindowPoint2WorldCoord**(`clickPointInWindow`): [`Point`](../type-aliases/Point.md)

Defined in: [boardify/board.ts:317](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L317)

#### Parameters

##### clickPointInWindow

[`Point`](../type-aliases/Point.md)

The point in window coordinates to convert.

#### Returns

[`Point`](../type-aliases/Point.md)

The converted point in world coordinates.

#### Translation Block

Converts a point from window coordinates to world coordinates.

***

### on()

> **on**\<`K`\>(`eventName`, `callback`): [`UnSubscribe`](../type-aliases/UnSubscribe.md)

Defined in: [boardify/board.ts:333](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L333)

#### Type Parameters

• **K** *extends* keyof [`CameraEventMap`](../type-aliases/CameraEventMap.md)

#### Parameters

##### eventName

`K`

The event name to listen for. The events are "pan", "zoom", and "rotate".

##### callback

(`event`, `cameraState`) => `void`

The callback function to call when the event is triggered. The event provided to the callback is different for the different events.

#### Returns

[`UnSubscribe`](../type-aliases/UnSubscribe.md)

The converted point in world coordinates.

#### Translation Block

Add an camera movement event listener. The events are "pan", "zoom", and "rotate".

***

### onInput()

> **onInput**\<`K`\>(`eventName`, `callback`): [`UnsubscribeToUserRawInput`](../type-aliases/UnsubscribeToUserRawInput.md)

Defined in: [boardify/board.ts:344](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L344)

#### Type Parameters

• **K** *extends* keyof [`RawUserInputEventMap`](../type-aliases/RawUserInputEventMap.md)

#### Parameters

##### eventName

`K`

##### callback

(`event`) => `void`

#### Returns

[`UnsubscribeToUserRawInput`](../type-aliases/UnsubscribeToUserRawInput.md)

#### Translation Block

Add an input event listener. The events are "pan", "zoom", and "rotate". This is different from the camera event listener as this is for input events. 
Input event does not necesarily mean that the camera will move. The input event is the event that is triggered when the user interacts with the board.

***

### setMaxTransWidthAlignedMin()

> **setMaxTransWidthAlignedMin**(`value`): `void`

Defined in: [boardify/board.ts:393](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L393)

#### Parameters

##### value

`number`

#### Returns

`void`

***

### step()

> **step**(`timestamp`): `void`

Defined in: [boardify/board.ts:295](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L295)

#### Parameters

##### timestamp

`number`

#### Returns

`void`

#### Translation Block

This is the step function that is called in the animation frame. This function is responsible for updating the canvas context and the camera state.

## LifeCycle

### setup()

> **setup**(): `void`

Defined in: [boardify/board.ts:129](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L129)

#### Returns

`void`

#### Translation Block

This function is used to set up the board. It adds all the event listeners and starts the resize observer and the attribute observer.

***

### tearDown()

> **tearDown**(): `void`

Defined in: [boardify/board.ts:139](https://github.com/niuee/board/blob/e6c1edcccf6525a0cc9088782c7c4653e837f533/src/boardify/board.ts#L139)

#### Returns

`void`

#### Translation Block

This function is used to clean up the board. It removes all the event listeners and disconnects the resize observer and the attribute observer.
