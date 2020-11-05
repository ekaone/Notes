## Grid responsive for Chakra-UI

```
<Grid
  templateColumns={{
    lg: "repeat(3, 1fr)",
    md: "repeat(2, 1fr)",
    sm: "repeat(1, 1fr)"
  }}
  gap={5}
  maxWidth="86em"
  ml="auto"
  mr="auto"
>
  {Array(6)
    .fill("")
    .map((_, index) => (
      <MyBox key="index" />
    ))}
</Grid>
```