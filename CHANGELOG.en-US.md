# CHANGELOG
## 1.0.3 (2020-03-25)
### Features
- `$NMessage`, `$NNotification`, `$NConfirm`'s theme will be applied on their children components.
### Fixes
- View measuring element will confict when multiple naive-ui exist.
- `validate` method of `n-form-item`  won't be resolved for some validator.
- `$NConfirm`'s theme doesn't follow `n-config-provider`'s theme.

## 1.0.2 (2020-03-23)
### Fixes
- `n-transfer`'s options are not reinitialized after value changes.
- `n-nimbus-service-layout` (deprecated) doesn't deal with the compatibility of Vue Router(under 3.1)'s `push` method.

## 1.0.1 (2020-03-21)
### Features
- Add `'bar'` & `'arrow-circle'` on `show-trigger` prop of `n-layout-sider`.
### Fixes
- Rails of `n-scrollbar` shadow mouse event.