# Dummy hook-me

This fork of TClient adds one setting, `cl_dummy_hook_me`.

When it is 1, holding `cl_dummy_hook` makes the dummy aim at your main tee and hook you (for messing around with hookfly). Letting go gives the dummy its own aim back. Dummy copy works as normal.

Example binds:

```
cl_dummy_hook_me 1
bind lctrl "+toggle cl_dummy_hook 1 0"
```

Only two files are changed: `src/engine/shared/config_variables.h` and `src/game/client/gameclient.cpp`. Meant for fun on your own server, not for ranked times.
