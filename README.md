# avtt-catalog

The default catalog of [avtt](https://github.com/Thedougler/avtt) extensions (ADR 0027). `avtt ext search <terms>` searches it and `avtt ext add <name>` resolves names through it.

List an extension by opening a pull request that adds an entry to `catalog.yaml`:

```yaml
entries:
  - name: corruption
    source: https://github.com/acme/avtt-corruption#v1.0.0
    description: Corruption tracks for dark campaigns
```

Being listed carries no trust: the DM still confirms each extension with `avtt ext trust`.
