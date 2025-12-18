```
sed -i "s/^Exercise/## Exercise/" special_vocabularies.md
sed -i '/^[#]/b; /^[[:space:]]*$/b; s/^/- /' special_vocabularies.md
```

Replace "- - " with "- "