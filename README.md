# falsegreen-fixture

A small repository that [falsegreen](https://github.com/cj-vana/falsegreen) runs its remote mode
against. Its workflow has one real gate (`node --test`) and one dead gate (`node --test || true`),
so a remote run should report the second.

Branches named `falsegreen/...` are created and deleted by those runs. Nothing here is meant to be
used as a library.

MIT licensed.
