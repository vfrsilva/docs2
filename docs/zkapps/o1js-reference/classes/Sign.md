[o1js](../README.md) / [Modules](../modules.md) / Sign

# Class: Sign

**`Deprecated`**

`CircuitValue` is deprecated in favor of [Struct](../modules.md#struct), which features a simpler API and better typing.

## Hierarchy

- [`CircuitValue`](CircuitValue.md)

  ↳ **`Sign`**

## Table of contents

### Constructors

- [constructor](Sign.md#constructor)

### Properties

- [value](Sign.md#value)

### Accessors

- [minusOne](Sign.md#minusone)
- [one](Sign.md#one)

### Methods

- [assertEquals](Sign.md#assertequals)
- [equals](Sign.md#equals)
- [isConstant](Sign.md#isconstant)
- [isPositive](Sign.md#ispositive)
- [mul](Sign.md#mul)
- [neg](Sign.md#neg)
- [toConstant](Sign.md#toconstant)
- [toFields](Sign.md#tofields)
- [toJSON](Sign.md#tojson)
- [toString](Sign.md#tostring)
- [check](Sign.md#check)
- [emptyValue](Sign.md#emptyvalue)
- [fromFields](Sign.md#fromfields)
- [fromJSON](Sign.md#fromjson)
- [fromObject](Sign.md#fromobject)
- [sizeInFields](Sign.md#sizeinfields)
- [toAuxiliary](Sign.md#toauxiliary)
- [toConstant](Sign.md#toconstant-1)
- [toFields](Sign.md#tofields-1)
- [toInput](Sign.md#toinput)
- [toJSON](Sign.md#tojson-1)

## Constructors

### constructor

• **new Sign**(`...props`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `...props` | `any`[] |

#### Inherited from

[CircuitValue](CircuitValue.md).[constructor](CircuitValue.md#constructor)

#### Defined in

[lib/circuit_value.ts:72](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/circuit_value.ts#L72)

## Properties

### value

• **value**: [`Field`](Field.md)

#### Defined in

[lib/int.ts:711](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/int.ts#L711)

## Accessors

### minusOne

• `Static` `get` **minusOne**(): [`Sign`](Sign.md)

#### Returns

[`Sign`](Sign.md)

#### Defined in

[lib/int.ts:716](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/int.ts#L716)

___

### one

• `Static` `get` **one**(): [`Sign`](Sign.md)

#### Returns

[`Sign`](Sign.md)

#### Defined in

[lib/int.ts:713](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/int.ts#L713)

## Methods

### assertEquals

▸ **assertEquals**(`x`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`Sign`](Sign.md) |

#### Returns

`void`

#### Inherited from

[CircuitValue](CircuitValue.md).[assertEquals](CircuitValue.md#assertequals)

#### Defined in

[lib/circuit_value.ts:160](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/circuit_value.ts#L160)

___

### equals

▸ **equals**(`x`): [`Bool`](Bool.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`Sign`](Sign.md) |

#### Returns

[`Bool`](Bool.md)

#### Inherited from

[CircuitValue](CircuitValue.md).[equals](CircuitValue.md#equals)

#### Defined in

[lib/circuit_value.ts:156](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/circuit_value.ts#L156)

___

### isConstant

▸ **isConstant**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CircuitValue](CircuitValue.md).[isConstant](CircuitValue.md#isconstant)

#### Defined in

[lib/circuit_value.ts:164](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/circuit_value.ts#L164)

___

### isPositive

▸ **isPositive**(): [`Bool`](Bool.md)

#### Returns

[`Bool`](Bool.md)

#### Defined in

[lib/int.ts:745](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/int.ts#L745)

___

### mul

▸ **mul**(`y`): [`Sign`](Sign.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`Sign`](Sign.md) |

#### Returns

[`Sign`](Sign.md)

#### Defined in

[lib/int.ts:742](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/int.ts#L742)

___

### neg

▸ **neg**(): [`Sign`](Sign.md)

#### Returns

[`Sign`](Sign.md)

#### Defined in

[lib/int.ts:739](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/int.ts#L739)

___

### toConstant

▸ **toConstant**(): [`Sign`](Sign.md)

#### Returns

[`Sign`](Sign.md)

#### Inherited from

[CircuitValue](CircuitValue.md).[toConstant](CircuitValue.md#toconstant)

#### Defined in

[lib/circuit_value.ts:152](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/circuit_value.ts#L152)

___

### toFields

▸ **toFields**(): [`Field`](Field.md)[]

#### Returns

[`Field`](Field.md)[]

#### Inherited from

[CircuitValue](CircuitValue.md).[toFields](CircuitValue.md#tofields)

#### Defined in

[lib/circuit_value.ts:144](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/circuit_value.ts#L144)

___

### toJSON

▸ **toJSON**(): `any`

#### Returns

`any`

#### Inherited from

[CircuitValue](CircuitValue.md).[toJSON](CircuitValue.md#tojson)

#### Defined in

[lib/circuit_value.ts:148](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/circuit_value.ts#L148)

___

### toString

▸ **toString**(): `string`

#### Returns

`string`

#### Defined in

[lib/int.ts:748](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/int.ts#L748)

___

### check

▸ `Static` **check**(`x`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`Sign`](Sign.md) |

#### Returns

`void`

#### Overrides

[CircuitValue](CircuitValue.md).[check](CircuitValue.md#check)

#### Defined in

[lib/int.ts:719](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/int.ts#L719)

___

### emptyValue

▸ `Static` **emptyValue**(): [`Sign`](Sign.md)

#### Returns

[`Sign`](Sign.md)

#### Defined in

[lib/int.ts:723](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/int.ts#L723)

___

### fromFields

▸ `Static` **fromFields**<`T`\>(`this`, `xs`): `InstanceType`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `xs` | [`Field`](Field.md)[] |

#### Returns

`InstanceType`<`T`\>

#### Inherited from

[CircuitValue](CircuitValue.md).[fromFields](CircuitValue.md#fromfields)

#### Defined in

[lib/circuit_value.ts:168](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/circuit_value.ts#L168)

___

### fromJSON

▸ `Static` **fromJSON**<`T`\>(`x`): `InstanceType`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | ``"Positive"`` \| ``"Negative"`` |

#### Returns

`InstanceType`<`T`\>

#### Overrides

[CircuitValue](CircuitValue.md).[fromJSON](CircuitValue.md#fromjson)

#### Defined in

[lib/int.ts:734](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/int.ts#L734)

___

### fromObject

▸ `Static` **fromObject**<`T`\>(`this`, `value`): `InstanceType`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `value` | `NonMethods`<`InstanceType`<`T`\>\> |

#### Returns

`InstanceType`<`T`\>

#### Inherited from

[CircuitValue](CircuitValue.md).[fromObject](CircuitValue.md#fromobject)

#### Defined in

[lib/circuit_value.ts:89](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/circuit_value.ts#L89)

___

### sizeInFields

▸ `Static` **sizeInFields**(): `number`

#### Returns

`number`

#### Inherited from

[CircuitValue](CircuitValue.md).[sizeInFields](CircuitValue.md#sizeinfields)

#### Defined in

[lib/circuit_value.ts:96](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/circuit_value.ts#L96)

___

### toAuxiliary

▸ `Static` **toAuxiliary**(): []

#### Returns

[]

#### Inherited from

[CircuitValue](CircuitValue.md).[toAuxiliary](CircuitValue.md#toauxiliary)

#### Defined in

[lib/circuit_value.ts:118](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/circuit_value.ts#L118)

___

### toConstant

▸ `Static` **toConstant**<`T`\>(`this`, `t`): `InstanceType`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `t` | `InstanceType`<`T`\> |

#### Returns

`InstanceType`<`T`\>

#### Inherited from

[CircuitValue](CircuitValue.md).[toConstant](CircuitValue.md#toconstant-1)

#### Defined in

[lib/circuit_value.ts:207](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/circuit_value.ts#L207)

___

### toFields

▸ `Static` **toFields**<`T`\>(`this`, `v`): [`Field`](Field.md)[]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `v` | `InstanceType`<`T`\> |

#### Returns

[`Field`](Field.md)[]

#### Inherited from

[CircuitValue](CircuitValue.md).[toFields](CircuitValue.md#tofields-1)

#### Defined in

[lib/circuit_value.ts:101](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/circuit_value.ts#L101)

___

### toInput

▸ `Static` **toInput**(`x`): `HashInput`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`Sign`](Sign.md) |

#### Returns

`HashInput`

#### Overrides

[CircuitValue](CircuitValue.md).[toInput](CircuitValue.md#toinput)

#### Defined in

[lib/int.ts:726](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/int.ts#L726)

___

### toJSON

▸ `Static` **toJSON**(`x`): ``"Positive"`` \| ``"Negative"``

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`Sign`](Sign.md) |

#### Returns

``"Positive"`` \| ``"Negative"``

#### Overrides

[CircuitValue](CircuitValue.md).[toJSON](CircuitValue.md#tojson-1)

#### Defined in

[lib/int.ts:729](https://github.com/o1-labs/o1js/blob/fec4d35f/src/lib/int.ts#L729)
