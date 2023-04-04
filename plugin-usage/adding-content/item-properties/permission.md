# Permission

### Example item permission

```yaml
  my_armor_simple_helmet:
    display_name: my_armor_simple helmet
    permission: my_armor_simple
    resource:
      generate: true
    durability:
      max_custom_durability: 275
    specific_properties:
      armor:
        slot: head
        color: '#ff0001'
    attribute_modifiers:
      head:
        armor: 9
        armorToughness: 1
```

## How to allow crafting

Permission: `ia.user.recipe.my_armor_simple`

## How to make the item visible in the `/ia` gui

To allow your players to **see** this item in `/ia` GUI you have to give them permission: `ia.user.ia.seeitem.my_armor_simple`

{% hint style="info" %}
Remember to give them permission `ia.user.ia` to let them use `/ia` command
{% endhint %}

{% hint style="warning" %}
Remember to create a [category ](../../ia.md)for the `/ia` GUI.
{% endhint %}

## Read more about permissions

{% content-ref url="../../permissions.md" %}
[permissions.md](../../permissions.md)
{% endcontent-ref %}