---
title: Configuring applications
intro: 'You can configure internal application settings for {% data variables.location.product_location %}.'
redirect_from:
  - /enterprise/admin/installation/configuring-applications
  - /enterprise/admin/configuration/configuring-applications
  - /admin/configuration/configuring-applications
versions:
  ghes: '*'
type: how_to
topics:
  - Enterprise
  - Fundamentals
---
## Adjusting image caching

You can choose the amount of time that {% data variables.location.product_location %} caches avatars. When you increase the cache time, you increase the amount of time a user's avatar will take to load. Configuring the cache time with too low a value can overload {% data variables.location.product_location %} work processes.

{% data reusables.enterprise_site_admin_settings.access-settings %}
{% data reusables.enterprise_site_admin_settings.management-console %}
3. In the "Settings" sidebar, click **Applications**.
4. Under "Avatar image cache time (seconds)", type the number of seconds that you would like {% data variables.location.product_location %} to cache avatar images.
{% data reusables.enterprise_management_console.save-settings %}
