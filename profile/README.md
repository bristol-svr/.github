# Colstonjs

Fast, simple and lightweight Web/API framework for [Bunjs](https://bun.sh) 🚀.

```typescript
import Colston, { Context } from "colstonjs";

const app = new Colston();
app.get("/", (ctx: Context) => {
  return ctx.status(200).text('hello colston');
});

app.listen(8000, () => console.log(`:listening`));
```

## License
This license applied to the whole project, see [LICENSE](/LICENSE.md)