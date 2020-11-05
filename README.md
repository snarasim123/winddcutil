# winddcutil
Windows implementation of the ddcutil Linux program for querying and changing monitor settings, such as brightness and color levels.

## Usage
```
Usage: windcutil command [<arg> ...]
Commands:
        detect                                         Detect monitors
        capabilities <display-id>                      Query monitor capabilities
        getvcp <display-id> <feature-code>             Report VCP feature value
        setvcp <display-id> <feature-code> <new-value> Set VCP feature value
```
