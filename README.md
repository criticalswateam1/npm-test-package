# My First NPM Package!
Hello this is my first NPM Package and its called 'shadowizard' and you can make your own plugin like this at:  https://www.youtube.com/watch?v=4zzbNac6f6Q

## What is this?

Get perfect shadows every time for non-designer.

# Installation

`npm i @devx11/my-test-package`

Then..

```
import { shadowizard } from 'shadowizard';

shadowizard({
    shadow_type: 'soft',
    padding: false
});
```

## Options

Shadowizard supports 2 options, both of which are optional:

* *shadow_type* - _hard / soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)
