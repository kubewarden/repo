This is a [manifest
repo](https://gerrit.googlesource.com/git-repo/+/master/docs/manifest-format.md)
for the [`repo`
tool](https://gerrit.googlesource.com/git-repo/+/refs/heads/master/README.md).

This contains all Kubewarden-related repos, so it's straightforward to
keep all of them in sync and up to date. It is also a good way to
develop on branches when branching impacts several repositories.

## Cloning everything

Run:

```shell
$ mkdir kubewarden
$ cd kubewarden
$ repo init git@github.com:kubewarden/repo.git
$ repo sync
```

Refer to the [`repo`
documentation](https://source.android.com/setup/develop/repo) to learn
more about its features.
