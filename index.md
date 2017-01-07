#
# chat related #
# Change "broadcast" to "message" if you would like to make join messages slient #
on join:
    broadcast "&7 %player%&f has joined the server" 
# Change "broadcast" to "message" if you would like to make leave messages slient #
on leave:
    broadcast "&7 %player%&f has left the server"
# Change "broadcast" to "message" if you would like to make welcome messages slient #
on first join:
    broadcast "&7 %player%&f has joined the server for the first time"
# You are able to change the time and message #
every 2 minutes:
    broadcast "&7&m----------------------------------------------------------------"
    broadcast "&a AmicusStudios&8 |&f this broadcast will exicute every (2 minutes)"
    broadcast "&7&m----------------------------------------------------------------"
# Chat format #
on chat:
    broadcast "&a %player%&7:&f %message%"
# More coming soon #
