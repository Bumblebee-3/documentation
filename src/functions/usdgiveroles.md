---
description: 'Give Roles, to the User ID.'
---

# $giveRoles

As example, below is setting, the User ID, to retrieve the Role.

`$giveRoles[Guild ID;User ID;Role ID]`

```javascript
bot.command({
name: "giverole", 
code: `
$giveRoles[$guildID;397881368715067422;773353340674900029]`
})
```

