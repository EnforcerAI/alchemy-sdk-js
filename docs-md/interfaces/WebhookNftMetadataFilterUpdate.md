[alchemy-sdk](../README.md) / [Exports](../modules.md) / WebhookNftMetadataFilterUpdate

# Interface: WebhookNftMetadataFilterUpdate

Params object when calling [NotifyNamespace.updateWebhook](../classes/NotifyNamespace.md#updatewebhook) to add and
remove NFT filters for a [NftMetadataUpdateWebhook](NftMetadataUpdateWebhook.md).

## Table of contents

### Properties

- [addMetadataFilters](WebhookNftMetadataFilterUpdate.md#addmetadatafilters)
- [removeMetadataFilters](WebhookNftMetadataFilterUpdate.md#removemetadatafilters)

## Properties

### addMetadataFilters

• **addMetadataFilters**: [`NftFilter`](NftFilter.md)[]

The filters to additionally track.

#### Defined in

[src/types/types.ts:2299](https://github.com/alchemyplatform/alchemy-sdk-js/blob/a162d40/src/types/types.ts#L2299)

___

### removeMetadataFilters

• **removeMetadataFilters**: [`NftFilter`](NftFilter.md)[]

Existing filters to remove.

#### Defined in

[src/types/types.ts:2301](https://github.com/alchemyplatform/alchemy-sdk-js/blob/a162d40/src/types/types.ts#L2301)