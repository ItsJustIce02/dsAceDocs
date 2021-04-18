# Modules
Modules are toggleable command groups for your server.

If you don't want to use a certain set of commands
use `-disable module-name`  
Alternatively you can also use `-enable module-name`

If you prefer to write out with `-config`,
you can do `-config enable module-name`

!!! note
    There is currently no disabling or enabling of modules.

## Module types
There are 3 types of modules.  

#### Togglable
Toggleable modules are ones you can enable and disable with `-enable`, `-disable`

#### Core
Core modules are ones you cannot disable or change values of.

#### Neutral
Neutral modules are disabled unless you provide something such as a channel.
