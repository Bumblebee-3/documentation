# $giveRole

This function gives a role to the specified user. This is generally fast then [$giveRoles](usdgiveroles.md)

```text
$giveRole[guildID;userID;roleID]
```

```javascript
bot.command({
name: "giveRole",
code: `
$giveRole[$guildID;535566311942651924;797332449314734141]
`

})
```

Giving the mentioned role to the mentioned user

```javascript
bot.command({
name: "giveRole",
code: `
$giveRole[$guildID;$mentioned[1];$mentionedRoles[1]]
`
})
```

