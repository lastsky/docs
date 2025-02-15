---
title: "Добавить правило в профиль безопасности"
description: "Следуя данной инструкции, вы сможете добавить правило в профиль безопасности."
---

# Добавить правило в профиль безопасности

В [профиле безопасности](../concepts/profiles.md) можно добавить базовые [правила](../concepts/rules.md), Smart Protection и WAF. Правила ARL [добавляются в профиле ARL](arl-rule-add.md).

{% list tabs group=instructions %}

- Консоль управления {#console}

  1. В [консоли управления]({{ link-console-main }}) выберите каталог, в котором вы хотите добавить правило в профиль безопасности.
  1. В списке сервисов выберите **{{ ui-key.yacloud.iam.folder.dashboard.label_smartwebsecurity }}**.
  1. Выберите профиль, в который вы хотите добавить правило.
  1. Нажмите кнопку ![plus-sign](../../_assets/console-icons/plus.svg) **{{ ui-key.yacloud.smart-web-security.form.button_add-rule }}**.
  1. В окне создания правила:

      {% include [add-rule](../../_includes/smartwebsecurity/add-rule.md) %}

- API {#api}

  {% include [api-profile-update](../../_includes/smartwebsecurity/api-profile-update.md) %}

{% endlist %}

### См. также {#see-also}

* [{#T}](rule-update.md)
* [{#T}](rule-delete.md)
