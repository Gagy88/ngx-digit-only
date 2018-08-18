# Angular DigitOnly Directive

An Angular directive only allows [0-9] in the input box when typing, pasting or drag/dropping.

[![Build Status](https://img.shields.io/travis/changhuixu/ngx-digit-only/master.svg?label=Travis%20CI&style=flat-square)](https://travis-ci.org/changhuixu/ngx-digit-only)
[![npm](https://img.shields.io/npm/v/ngx-digit-only.svg?style=flat-square)](https://www.npmjs.com/package/ngx-digit-only)

## [Demo](https://stackblitz.com/github/changhuixu/ngx-digit-only)

## Usage

```typescript
// in your Angular module
import { DigitOnlyModule } from '@uiowa/digit-only';

@NgModule({
  declarations: [
    ...
  ],
  imports: [
    BrowserModule,
    DigitOnlyModule
  ],
  ...
})
export class YourModule { }
```

```html
// in your component.html
<input type="text" digitOnly>
```
