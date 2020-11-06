## Avoid loading on SWR

```
const { data, error } = useSWR(true ? `/api/user` : null, fetcher);
```