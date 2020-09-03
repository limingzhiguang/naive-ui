# 图标
我喜欢用图标当头像。
```html
<n-avatar>
  <n-icon>
    <md-cash />
  </n-icon>
</n-avatar>
```
```js
import mdCash from 'naive-ui/lib/icons/md-cash'
import mdContacts from 'naive-ui/lib/icons/md-contacts'
import iosContacts from 'naive-ui/lib/icons/ios-contacts'

export default {
  components: {
    mdCash,
    mdContacts,
    iosContacts
  }
}
```