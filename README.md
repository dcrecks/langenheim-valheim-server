# friendly-neighborhood-valheim-server

## World troubleshooting
The container seems to hold residual info. Make sure you add and overwrite the save files in `saves/worlds_local/` to include `<Server Name>` and `Dedicated` for both the `.db` and `.fwl` files. `docker system prune` seems to help a bit.


