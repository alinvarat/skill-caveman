# Mode commands
`/caveman ultra` and `/caveman wenyan` use ultracave and megacave respectively if available; do not claim an unavailable skill was loaded.
For `/caveman status`, report the hook's `Caveman mode: <mode>` if present. Otherwise report the mode followed before the command plus `(not tracked by this host)`. Loading the skill to answer status does not activate it; do not infer mode from a configured default. Stop/normal mode switches it off; confirm in one line.
