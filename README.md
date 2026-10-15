# Scoop bucket for Migrax

[Migrax](https://migrax.org/) generates database migrations from your JPA entities.

```powershell
scoop bucket add migrax https://github.com/fsmutimeer/scoop-migrax
scoop install migrax
migrax version
```

Migrax needs Java 17 or newer. If you don't have it: `scoop bucket add java` and
`scoop install java/temurin21-jdk`.

Update with `scoop update migrax`. This bucket is updated automatically by every Migrax release;
see the [installation guide](https://migrax.org/getting-started/installation/).
