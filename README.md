A tiny utility for managing ssh_config fragments handled by (poet)[https://github.com/awendt/poet].


<pre>
usage: ptssh [-h] [-c CONFIG] [-r] {enable,disable,inventory} ...

Enable/disable ssh config fragments for poet

positional arguments:
  {enable,disable,inventory}
    enable              Enable an ssh config fragment
    disable             Disable an ssh config fragment
    inventory           Show ssh fragment statuses

optional arguments:
  -h, --help            show this help message and exit
  -c CONFIG, --config CONFIG
                        config.d directory managed by poet (default:
                        $HOME/.ssh/config.d)
  -r, --run             Run poet after taking action? (default: False)
</pre>
