# aggressor_snippets
A collection of random small Aggressor snippets that don't warrant their own repo

## locate
This Aggressor alias will call the underlying Linux OS command 'locate'. The envisioned use for this is when a custom defined alias is being used in CobaltStrike which requires the full path to a file on the host OS be specified. While built-in CobaltStrike commands feature tab complete for OS paths, custom defined aliases do not, and typing out or having to switch to a terminal to grab the full path to a file/tool is a pain.

