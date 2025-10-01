[**@waylis/core**](../index.md)

***

[@waylis/core](../index.md) / LineChart

# Interface: `LineChart`

Defined in: [src/message/types.ts:16](https://github.com/waylis/core/blob/ec4e52cc907d26692651cc5868e974b2792624f2/src/message/types.ts#L16)

Configuration for rendering a line chart.

More info: https://mantine.dev/charts/line-chart/

## Properties

### curveType?

```ts
optional curveType: 
  | "bump"
  | "linear"
  | "natural"
  | "monotone"
  | "step"
  | "stepBefore"
  | "stepAfter";
```

Defined in: [src/message/types.ts:24](https://github.com/waylis/core/blob/ec4e52cc907d26692651cc5868e974b2792624f2/src/message/types.ts#L24)

Curve interpolation type.

***

### data

```ts
data: Record<string, any>[];
```

Defined in: [src/message/types.ts:18](https://github.com/waylis/core/blob/ec4e52cc907d26692651cc5868e974b2792624f2/src/message/types.ts#L18)

Data points for the chart.

***

### dataKey

```ts
dataKey: string;
```

Defined in: [src/message/types.ts:20](https://github.com/waylis/core/blob/ec4e52cc907d26692651cc5868e974b2792624f2/src/message/types.ts#L20)

Key in each data object used for the X-axis.

***

### extra?

```ts
optional extra: Record<string, any>;
```

Defined in: [src/message/types.ts:26](https://github.com/waylis/core/blob/ec4e52cc907d26692651cc5868e974b2792624f2/src/message/types.ts#L26)

Any other parameters.

***

### series

```ts
series: {
  color?: string;
  label?: string;
  name: string;
  yAxisId?: string;
}[];
```

Defined in: [src/message/types.ts:22](https://github.com/waylis/core/blob/ec4e52cc907d26692651cc5868e974b2792624f2/src/message/types.ts#L22)

Series definitions (e.g. lines).

#### color?

```ts
optional color: string;
```

#### label?

```ts
optional label: string;
```

#### name

```ts
name: string;
```

#### yAxisId?

```ts
optional yAxisId: string;
```
