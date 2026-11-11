# rob-run-sdk

IL2CPP SDK of ROB RUN (Unity 6000.3.18f1), dumped from the game with [Il2CppDumper](https://github.com/Perfare/Il2CppDumper).

Each folder is one Steam build:

| Build | Folder |
| --- | --- |
| 26599424 (11 November 2026) | [`26599424`](26599424) |
| 26586703 (11 November 2026) | [`26586703`](26586703) |
| 26559853 (10 November 2026) | [`26559853`](26559853) |
| 26509119 (8 November 2026) | [`26509119`](26509119) |

| File | Contents |
| --- | --- |
| `dump.cs` | Every type with its fields, field offsets, properties and methods. Methods carry their RVA, offset and VA. |
| `script.zip` | `script.json` (zipped, it is over GitHub's 100 MB limit): method addresses, string literals and metadata usages for the IDA and Ghidra scripts. |
| `stringliteral.json` | String literals with their addresses. |
| `DummyDll/` | Dummy assemblies with the type metadata and no method bodies. Open them in dnSpy or ILSpy, or reference them from a project. |
