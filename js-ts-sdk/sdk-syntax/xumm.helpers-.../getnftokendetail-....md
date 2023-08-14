# getNftokenDetail( ... )

> This method is only available when using the SDK in a `JWT` context!

The `getNftokenDetail` method allows you to get basic XLS20 token information as fetched/parsed/cached for you by the XUMM backend.

**Note**: it's best to retrieve these results **yourself** instead of relying on the XUMM platform to get live XRPL transaction information!

```typescript
const txInfo = await Sdk.getNftokenDetail(tokenId);
```

Returns: [`<NftokenDetail>`](https://github.com/XRPL-Labs/XUMM-SDK/blob/master/src/types/Meta/NftokenDetail.ts)
