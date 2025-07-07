
### dependencies
- You need ```az```
- ```az``` ```account``` extention
    - install with ```az extension add --name account```
- Also ```fzf``` for interactive scripts
    - install with ```brew``` or something.


### How to run
<b>Recommended:</b> symlink ```myaz``` to a place that is in your ```$PATH```.

But you can scripts directly or add the whole directory to your path.

```
$ myaz 
$ myaz get-secret [vault] [secret]
$ myaz get-secret-interactive

or

$ get-secret [vault] [secret]
$ get-secret-interactive
```
