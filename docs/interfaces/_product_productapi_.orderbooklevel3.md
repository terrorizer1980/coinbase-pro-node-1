**[coinbase-pro-node](../README.md)**

> [Globals](../globals.md) / ["product/ProductAPI"](../modules/_product_productapi_.md) / OrderBookLevel3

# Interface: OrderBookLevel3

Full order book (non aggregated): Level 3 is only recommended for users wishing to maintain a full real-time order book using the websocket stream. Abuse of Level 3 via polling will cause your access to be limited or blocked.

## Hierarchy

- **OrderBookLevel3**

## Index

### Properties

- [asks](_product_productapi_.orderbooklevel3.md#asks)
- [bids](_product_productapi_.orderbooklevel3.md#bids)
- [sequence](_product_productapi_.orderbooklevel3.md#sequence)

## Properties

### asks

• **asks**: NonAggregatedOrder[]

_Defined in [src/product/ProductAPI.ts:128](https://github.com/bennycode/coinbase-pro-node/blob/06bdaca/src/product/ProductAPI.ts#L128)_

---

### bids

• **bids**: NonAggregatedOrder[]

_Defined in [src/product/ProductAPI.ts:129](https://github.com/bennycode/coinbase-pro-node/blob/06bdaca/src/product/ProductAPI.ts#L129)_

---

### sequence

• **sequence**: SequenceNumber

_Defined in [src/product/ProductAPI.ts:130](https://github.com/bennycode/coinbase-pro-node/blob/06bdaca/src/product/ProductAPI.ts#L130)_
