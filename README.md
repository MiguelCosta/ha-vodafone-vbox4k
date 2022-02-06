# Vodafone VBox 4K - Lovelace Card

I have the [Vodafone VBox 4K](https://manuaisonline.vodafone.pt/vodafone/vboxpro-4k-proprietary-os/) and I created a lovelace card using a [BroadLink RM4 mini](https://mauser.pt/catalog/product_info.php?cPath=44_121&products_id=096-7918) as remote.

## Issues

`Up` and `Down` buttons are not working correctly.

## My Card

![card](/assets/card2.png)

### Pre-requisites>

- Home Assistant Integration
    - BroadLink | https://www.home-assistant.io/integrations/broadlink/

- HACS Custom-Cards
    - custom:button-card | https://github.com/custom-cards/button-card

### Use the card

If you are using the same device you just need to copy all the card code and replace the entity_id by your own.

Entities to replace:

- `remote.broadlink_sala_remote`

## Vodafone device

![remote](/assets/remote.png)
