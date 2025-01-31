[@zeldafan0225/ai_horde](../README.md) / [Exports](../modules.md) / ActiveModel

# Interface: ActiveModel

## Hierarchy

- [`ActiveModelLite`](ActiveModelLite.md)

  ↳ **`ActiveModel`**

## Table of contents

### Properties

- [count](ActiveModel.md#count)
- [eta](ActiveModel.md#eta)
- [name](ActiveModel.md#name)
- [performance](ActiveModel.md#performance)
- [queued](ActiveModel.md#queued)

## Properties

### count

• `Optional` **count**: `number`

How many workers in this horde are running this model.

#### Inherited from

[ActiveModelLite](ActiveModelLite.md).[count](ActiveModelLite.md#count)

#### Defined in

[index.ts:2329](https://github.com/ZeldaFan0225/ai_horde/blob/4b01aad/index.ts#L2329)

___

### eta

• `Optional` **eta**: `number`

Estimated time in seconds for this model's queue to be cleared

#### Defined in

[index.ts:2322](https://github.com/ZeldaFan0225/ai_horde/blob/4b01aad/index.ts#L2322)

___

### name

• `Optional` **name**: `string`

The name of a model available by workers in this horde.

#### Inherited from

[ActiveModelLite](ActiveModelLite.md).[name](ActiveModelLite.md#name)

#### Defined in

[index.ts:2327](https://github.com/ZeldaFan0225/ai_horde/blob/4b01aad/index.ts#L2327)

___

### performance

• `Optional` **performance**: `number`

The average speed of generation for this model

#### Defined in

[index.ts:2318](https://github.com/ZeldaFan0225/ai_horde/blob/4b01aad/index.ts#L2318)

___

### queued

• `Optional` **queued**: `number`

The amount waiting to be generated by this model

#### Defined in

[index.ts:2320](https://github.com/ZeldaFan0225/ai_horde/blob/4b01aad/index.ts#L2320)
