**Why?**

This plugin solves the problem that chrome (or any other browser) doesn't support the autocomplete attribute anymore. It simply ignores the attribute, which is why i created this plugin.

**How to use**

```
import DisableAutocomplete from '@aacassandra/vue-disable-autocomplete';

Vue.use(DisableAutocomplete);
```

**HTML attribute**

You should add this attribute `autocomplete="off"` to the HTML input elements you want to disable autocomplete. For example:

```
<input type="email" name="email" autocomplete="off">
```
