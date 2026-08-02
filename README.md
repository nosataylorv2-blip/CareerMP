# CareerMP 0.39.18 for BeamNG.drive 0.39

This package contains both the CareerMP server plugin and the client mod sent to players by BeamMP.

Included versions: client 0.39.18, server 0.39.8.

## Installation

1. Stop the BeamMP server.
2. In `Resources/Client`, remove older or renamed `CareerMP*.zip` files. Do not remove unrelated mods.
3. Extract this package into the BeamMP server directory, alongside `BeamMP-Server.exe`.
4. Allow the included `Resources` folder to merge with the server's existing `Resources` folder.
5. Set `Map = "/levels/west_coast_usa/info.json"` in `ServerConfig.toml`.
6. Set `MaxCars = 100` or higher.
7. Start the server and join normally through BeamMP.

After startup, a server with no unrelated client mods should report `Loaded 1 Mods`. If it reports more, check `Resources/Client` for an older CareerMP ZIP before joining.

Career saves remain local to each player. Players can select, create, switch, and delete saves through the normal Career interface.

Automatic CareerMP updates are disabled for this compatibility build so the repaired 0.39 files are not replaced by an older upstream version.
