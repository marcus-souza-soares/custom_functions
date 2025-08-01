# custom_functions
My custom functions and alias to improve the productivity.


- `git clone <this-repo>` in your personal path ($HOME)
- Put this code snippet in the your .zshrc (or .bashrc if you are not using zsh) file
```sh
# custom functions
if [ -f ~/.custom_functions/.aliases ]; then
  . ~/custom_functions/.aliases
fi
```

Then, run `source ~/.zshrc` or `source ~/.bashc` according to the shell you are using.
