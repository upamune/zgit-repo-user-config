# zgit-repo-user-config

This zsh plugin was developed for auto user information configuration of git repositories under user's specified directory.

## Usage

### First time

Write configuration in your `.zshenv` as follows.

```
export ZGITREPO_USER_CONFIG_FILE=$HOME/.zgitrepo_user.config
```

You can set this path of configuration file as your favorite path and file name.

### Normal state

1. Load `zgit-repo-user-config`.
2. In parent directory, type `zgit-repo-user-config -a` for register directory as parent directory.
3. Call this plugin in `preexec`.
<wip>

## License

See `LICENSE`.