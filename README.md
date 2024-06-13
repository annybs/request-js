# Request

A tiny, dependency-free library for performing simple XMLHttpRequests.

## Usage

```ts
import request from '@annybs/request-js'

async function main() {
  const res = await request.get('https://google.com')
  console.log(res.string)
}

main()
```

See the [Request and Response types](./src/types.ts) for more insight.
