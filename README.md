# redis cookbook

Install package installation of redis on hosts that match `platform_family` of `rhel` or `debian`.

# Requirements

* [build-essentials](http://community.opscode.com/cookbooks/build-essential)
* [yum](http://community.opscode.com/cookbooks/yum)
* [apt](http://community.opscode.com/cookbooks/apt)

## This has been tested on:

* CentOS 6.3

# Usage

    // file: nodes/host.json
    {
        "run_list": [ "recipe[redis]" ]
    }

# Author

Author:: Joshua P. Mervine (<joshua@mervine.net>)