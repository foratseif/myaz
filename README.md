
### Dependencies
- ```az```
- ```account``` extention for ```az```
    - (install with ```az extension add --name account```)
- ```jq``` is needed for scripts to process json
- ```fzf``` for interactive scripts


### How to run
<b>Recommended:</b> symlink ```myaz``` to a place that is in your ```$PATH```.

But you can run scripts directly or add the whole directory to your path. You do you.

```
$ myaz 
$ myaz list-vaults 
$ myaz list-secrets [vault] 
$ myaz get-secret [vault] [secret]
$ myaz get-secret-interactive
$ myaz list-sub
$ myaz switch-sub [subscription-id]
$ myaz switch-sub-interactive

or

$ get-secret-interactive
$ list-vaults 
$ list-secrets [vault] 
$ get-secret [vault] [secret]
$ list-sub
$ switch-sub [subscription-id]
$ switch-sub-interactive
```
