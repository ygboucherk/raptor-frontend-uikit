# Raptor UIkit

## Install

In project file package.json in prop "dependencies" add "@raptorswap-uikit" : 

### Theme

Before using raptorswap UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Add new
when you add new changes yarn build then push new /dist in server branch