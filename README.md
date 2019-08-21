```typescript
type Link = LinkWithEncrypt | LinkWithoutEncrypt

type LinkWithEncrypt = {
  data: string;
  encrypt: true;
}

type LinkWithoutEncrypt = {
  data: string | string[];
  encrypt: false;
}
```