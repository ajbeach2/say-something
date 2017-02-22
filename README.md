# say-something

```bash
cat /usr/share/dict/words | perl -e 'print join("", sort { rand(1) <=> 0.5 } <>);' | say &
```
