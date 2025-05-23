# Internal Built In Dictionaries

!!! Info 
	This is an **Unofficial** and fan-made project. Please refrain from seeking support from Riot or Valorant.

!!! Info "How To Invoke"
	```c#
	using RadiantConnect.Methods;

	ValorantTables.DICTIONARY
	```

## GunIdToGun
```C#
public static Dictionary<string, string> GunIdToGun = new()
{
	{ "0afb2636-4093-c63b-4ef1-1e97966e2a3e", "SPIKE" },
	{ "3de32920-4a8f-0499-7740-648a5bf95470", "Golden Gun" },
	{ "2f59173c-4bed-b6c3-2191-dea9b58be9c7", "Melee" },
	{ "63e6c2b6-4a8e-869c-3d4c-e38355226584", "Odin" },
	{ "55d8a0f4-4274-ca67-fe2c-06ab45efdf58", "Ares" },
	{ "9c82e19d-4575-0200-1a81-3eacf00cf872", "Vandal" },
	{ "ae3de142-4d85-2547-dd26-4e90bed35cf7", "Bulldog" },
	{ "ee8e8d15-496b-07ac-e5f6-8fae5d4c7b1a", "Phantom" },
	{ "ec845bf4-4f79-ddda-a3da-0db3774b2794", "Judge" },
	{ "910be174-449b-c412-ab22-d0873436b21b", "Bucky" },
	{ "44d4e95c-4157-0037-81b2-17841bf2e8e3", "Frenzy" },
	{ "29a0cfab-485b-f5d5-779a-b59f85e204a8", "Classic" },
	{ "1baa85b4-4c70-1284-64bb-6481dfc3bb4e", "Ghost" },
	{ "e336c6b8-418d-9340-d77f-7a9e4cfe0702", "Sheriff" },
	{ "42da8ccc-40d5-affc-beec-15aa47b42eda", "Shorty" },
	{ "a03b24d3-4319-996d-0f8c-94bbfba1dfc7", "Operator" },
	{ "4ade7faa-4cf1-8376-95ef-39884480959b", "Guardian" },
	{ "c4883e50-4494-202c-3ec3-6b8a9284f00b", "Marshal" },
	{ "462080d1-4035-2937-7c09-27aa2a5c27a7", "Spectre" },
	{ "f7e1b454-4ad4-1063-ec0a-159e56b58941", "Stinger" },
	{ "5f0aaf7a-4289-3998-d5ff-eb9a5cf7ef5c", "Outlaw" }
};
```

| **Internal Gun ID** | **Gun Name** |
|------------------------|--------------------------|
| `5f0aaf7a-4289-3998-d5ff-eb9a5cf7ef5c` | `Outlaw`|


## InternalGameModeToGameMode
```C#
public static readonly Dictionary<string, string> InternalGameModeToGameMode = new()
{
	{ "newmap", "New Map"},
	{ "competitive", "Competitive"},
	{ "unrated", "Unrated"},
	{ "swiftplay", "Swiftplay"},
	{ "spikerush", "Spike Rush"},
	{ "deathmatch", "Deathmatch"},
	{ "ggteam", "Escalation"},
	{ "onefa", "Replication"},
	{ "hurm", "Team Deathmatch"},
	{ "custom", "Custom"},
	{ "snowball", "Snowball Fight"},
	{ "", "Custom"}
};
```

| **Internal Gun ID** | **Gun Name** |
|------------------------|--------------------------|
| `ggteam` | `Escalation`|


## CurrencyIdToCurrency
```C#
public static Dictionary<string, string> CurrencyIdToCurrency = new()
{
	{ "85ad13f7-3d1b-5128-9eb2-7cd8ee0b5741", "VP" },
	{ "85ca954a-41f2-ce94-9b45-8ca3dd39a00d", "Kingdom Credits" },
	{ "f08d4ae3-939c-4576-ab26-09ce1f23bb37", "Free Agents" },
	{ "e59aa87c-4cbf-517a-5983-6e81511be9b7", "Radianite Points" },
};
```

| **Currency ID** | **Currency Name** |
|------------------------|--------------------------|
| `e59aa87c-4cbf-517a-5983-6e81511be9b7` | `Radianite Points`|

## InternalMapNames
```C#
public static Dictionary<string, string> InternalMapNames = new()
{
	{ "Juliett", "Sunset" },
	{ "Jam", "Lotus" },
	{ "Pitt", "Pearl" },
	{ "Canyon", "Fracture" },
	{ "Foxtrot", "Breeze" },
	{ "Port", "Icebox" },
	{ "Ascent", "Ascent" },
	{ "Bonsai", "Split" },
	{ "Triad", "Haven" },
	{ "Duality", "Bind" },
	{ "7eaecc1b-4337-bbf6-6ab9-04b8f06b3319", "Ascent" },
	{ "d960549e-485c-e861-8d71-aa9d1aed12a2", "Split" },
	{ "b529448b-4d60-346e-e89e-00a4c527a405", "Fracture" },
	{ "2c9d57ec-4431-9c5e-2939-8f9ef6dd5cba", "Bind" },
	{ "2fb9a4fd-47b8-4e7d-a969-74b4046ebd53", "Breeze" },
	{ "690b3ed2-4dff-945b-8223-6da834e30d24", "District" },
	{ "12452a9d-48c3-0b02-e7eb-0381c3520404", "Kasbah" },
	{ "2c09d728-42d5-30d8-43dc-96a05cc7ee9d", "Drift" },
	{ "de28aa9b-4cbe-1003-320e-6cb3ec309557", "Piazza" },
	{ "2fe4ed3a-450a-948b-6d6b-e89a78e680a9", "Lotus" },
	{ "92584fbe-486a-b1b2-9faa-39b0f486b498", "Sunset" },
	{ "fd267378-4d1d-484f-ff52-77821ed10dc2", "Pearl" },
	{ "e2ad5c54-4114-a870-9641-8ea21279579a", "Icebox" },
	{ "ee613ee9-28b7-4beb-9666-08db13bb2244", "The Range" },
	{ "2bee0dc9-4ffe-519b-1cbd-7fbe763a6047", "Haven" }
};
```

| **Internal Map** | **Client Map** |
|------------------------|--------------------------|
| `Duality` | `Bind`|

## AgentIdToAgent
```C#
public static readonly Dictionary<string, string> AgentIdToAgent = new()
{
	{ "41fb69c1-4189-7b37-f117-bcaf1e96f1bf", "Astra" },
	{ "5f8d3a7f-467b-97f3-062c-13acf203c006", "Breach" },
	{ "9f0d8ba9-4140-b941-57d3-a7ad57c6b417", "Brimstone" },
	{ "22697a3d-45bf-8dd7-4fec-84a9e28c69d7", "Chamber" },
	{ "117ed9e3-49f3-6512-3ccf-0cada7e3823b", "Cypher" },
	{ "cc8b64c8-4b25-4ff9-6e7f-37b4da43d235", "Deadlock" },
	{ "dade69b4-4f5a-8528-247b-219e5a1facd6", "Fade" },
	{ "e370fa57-4757-3604-3648-499e1f642d3f", "Gekko" },
	{ "95b78ed7-4637-86d9-7e41-71ba8c293152", "Harbor" },
	{ "0e38b510-41a8-5780-5e8f-568b2a4f2d6c", "ISO" },
	{ "add6443a-41bd-e414-f6ad-e58d267f4e95", "Jett" },
	{ "1e58de9c-4950-5125-93e9-a0aee9f98746", "Killjoy" },
	{ "bb2a4828-46eb-8cd1-e765-15848195d751", "Neon" },
	{ "8e253930-4c05-31dd-1b6c-968525494517", "Omen" },
	{ "eb93336a-449b-9c1b-0a54-a891f7921d69", "Phoenix" },
	{ "f94c3b30-42be-e959-889c-5aa313dba261", "Raze" },
	{ "a3bfb853-43b2-7238-a4f1-ad90e9e46bcc", "Reyna" },
	{ "569fdd95-4d10-43ab-ca70-79becc718b46", "Sage" },
	{ "6f2a04ca-43e0-be17-7f36-b3908627744d", "Skye" },
	{ "320b2a48-4d9b-a075-30f1-1f93a9b638fa", "Sova" },
	{ "707eab51-4836-f488-046a-cda6bf494859", "Viper" },
	{ "7f94d92c-4234-0a36-9646-3a87eb8b5c89", "Yoru" },
	{ "601dbbe7-43ce-be57-2a40-4abd24953621", "KAY/O" }
};
```

| **Agent ID** | **Agent Name** |
|------------------------|--------------------------|
| `41fb69c1-4189-7b37-f117-bcaf1e96f1bf` | `Astra`|


## TierToRank
```C#
public static readonly Dictionary<long, string> TierToRank = new()
{
	{ 0, "Unranked" },
	{ 1, "Unranked" },
	{ 2, "Unranked" },
	{ 3, "Iron 1" },
	{ 4, "Iron 2" },
	{ 5, "Iron 3" },
	{ 6, "Bronze 1" },
	{ 7, "Bronze 2" },
	{ 8, "Bronze 3" },
	{ 9, "Silver 1" },
	{ 10, "Silver 2" },
	{ 11, "Silver 3" },
	{ 12, "Gold 1" },
	{ 13, "Gold 2" },
	{ 14, "Gold 3" },
	{ 15, "Platinum 1" },
	{ 16, "Platinum 2" },
	{ 17, "Platinum 3" },
	{ 18, "Diamond 1" },
	{ 19, "Diamond 2" },
	{ 20, "Diamond 3" },
	{ 21, "Ascendant 1" },
	{ 22, "Ascendant 2" },
	{ 23, "Ascendant 3" },
	{ 24, "Immortal 1" },
	{ 25, "Immortal 2" },
	{ 26, "Immortal 3" },
	{ 27, "Radiant" }
};
```

| **Internal Tier ID** | **Rank Name** |
|------------------------|--------------------------|
| `12` | `Gold 1`|
