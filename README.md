In this repo I will share some scripts that I use with GoldenGate.

[My Postman Collection with common REST API Actions](postman/OGG.postman_collection.json)

This script is heavily based on variables that can be configured at the session level (Current Value) or permanently (Initial Value), so take a minute to understand each variable.

![https://imgur.com/OM2XP10](https://i.imgur.com/OM2XP10.png)

It currently supports:

- User Creation(createUser)
- Credential Creation(createCredential)
- Distribution Path Creation(createDistPath)
- Add Schema Trandata(addTrandata)
- Extract Creation(createExtract)
- Create Checkpoint Table(createCkptTable)
- Create Replicat in the same deployment(createReplicatSameDeployment)



## [AdminClient Commands](adminclient)
- [Purge Trails](adminclient/purge_trails.md)
