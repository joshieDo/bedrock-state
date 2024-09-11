## OP-mainnet Bedrock world trie state

**Requires Git-LFS installed.**

```bash
git lfs pull && 
cat *.part > world_trie.zst &&
unzstd -d world_trie.zst -o world_trie.jsonl
```


```bash
$ sha256sum world_trie.jsonl
b2c2b6e7edb919a0b856b9fd9aa02b11ead5305e63cdb33386babd82b9bc4cfe  world_trie.jsonl
```
