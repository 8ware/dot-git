
Git·files
=========

[Website] | [Sources]

[Website]: https://git-scm.com/
[Sources]: https://git.kernel.org/pub/scm/git/git.git


Setup
-----

* `apt install git`
* `git clone https://github.com/8ware/dot-git.git ~/.config/git`

### `diff-highlight`

* `make -C ~/.config/git/diff-highlight`
* Configure `$PATH`
  ```sh
  if [ -d "$HOME/.config/git/bin" ] ; then
      PATH="$HOME/.config/git/bin:$PATH"
  fi
  ```

