---
Webseite: https://silencenight.de/
---

# Silencnight

## 0.2.3 (2021-10-24T16:33:00.150Z)

### New

- Add `ago` suffix to changelog dates

## 0.2.2 (2021-10-24T16:33:00.150Z)

### New

- Optimize text rendering
- Tweak text color, use lighter color
- Update [marked3](https://github.com/egoist/marked3) to make links open in new tab

## 0.2.0 (2021-10-24T16:33:00.150Z)

### New

Jetzt können Sie es auch als Vue-Komponente verwenden!

```vue
<template>
  <div id="app">
    <log-live 
      :changelog="changelog">
    </log-live>
  </div>
</template>

<script>
import { LogLive } from 'loglive'

export default {
  components: {
    LogLive
  },

  data() {
    return {
      changelog: '/changelog.md'
    }
  }
}
</script>
```

## 0.1.3 (2021-10-24T16:33:00.150Z)

### Fix

Fix regular expression for matching date in changelog title.

## 0.1.2 (2021-10-24T16:33:00.150Z)

### Fix

Remove debug log, thanks to [@FuryBean](https://github.com/furybean)

## 0.1.1 (2021-10-24T16:33:00.150Z)

### Fix

Tweak style of loading text, **smaller**!.

## 0.1.0 (2021-10-24T16:33:00.150Z)

### New

- Add transition effect to changelog body
- Add loading indicator

## 0.0.3 (2021-10-24T16:33:00.150Z)

### Fix

Tweak style for `<code>` span, simply wrap it with backticks!

## 0.0.2 (2021-10-24T16:33:00.150Z)

### Fix

Fix CSS align issue of `date` string, add a default style for code blocks. 💅

## 0.0.1 (2021-10-24T16:33:00.150Z)

### Initial

I'm just publising it to see if it works as expected, it still has a lot of spaces to improve but I feel this version would work just fine.
