
### dependencies
- ```az```
- ```account``` extention for ```az```
    - install with ```az extension add --name account```
- ```jq``` is needed for scripts to process json
- ```fzf``` for interactive scripts
    - install with ```brew``` or something.


### How to run
<b>Recommended:</b> symlink ```myaz``` to a place that is in your ```$PATH```.

But you can run scripts directly or add the whole directory to your path. You do you.

```
$ myaz 
$ myaz get-secret [vault] [secret]
$ myaz get-secret-interactive

or

$ get-secret [vault] [secret]
$ get-secret-interactive
```
