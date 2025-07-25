---
title: About the new billing platform
intro: Learn about the billing platform's key functionalities, and how it can help you manage your spending more effectively.
versions:
  feature: enhanced-billing-platform
redirect_from:
  - /billing/using-the-enhanced-billing-platform-for-enterprises/about-the-enhanced-billing-platform-for-enterprises
  - /billing/using-the-new-billing-platform/about-the-new-billing-platform-for-enterprises
  - /billing/using-the-new-billing-platform/about-the-new-billing-platform
  - /billing/using-the-new-billing-platform/getting-started-with-the-new-billing-platform
type: overview
topics:
  - Enterprise
  - Team
product: '{% data reusables.billing.enhanced-billing-platform-product %}'
shortTitle: About the new billing platform
---

The new billing platform provides better spending control and detailed usage insights with granular controls.

## Available products

The products shown in the new billing platform are determined by your {% data variables.product.github %} plan and subscriptions.

{% ifversion fpt %}

### Personal accounts on {% data variables.product.prodname_free_user %} or {% data variables.product.prodname_pro %}

* {% data variables.product.prodname_actions %}
* {% data variables.product.prodname_github_codespaces %}
* {% data variables.product.prodname_copilot %}
* {% data variables.product.prodname_registry %}
* {% data variables.large_files.product_name_long %}
* {% data variables.product.prodname_marketplace %}
* {% data variables.product.prodname_github_models %}
* {% data variables.product.prodname_sponsors %}

{% endif %}

### Organizations on {% data variables.product.prodname_team %} or {% data variables.product.prodname_free_team %}

* {% data variables.product.prodname_actions %}
* {% data variables.product.prodname_GH_cs_and_sp %} (only available with {% data variables.product.prodname_team %})
* {% data variables.product.prodname_github_codespaces %}
* {% data variables.product.prodname_copilot %}
* {% data variables.product.prodname_github_models %}
* {% data variables.product.prodname_registry %}
* {% data variables.large_files.product_name_long %}

{% ifversion ghec %}

### {% data variables.product.prodname_ghe_cloud %}

* {% data variables.product.prodname_actions %}
* {% data variables.product.prodname_GH_cs_and_sp %}
* {% data variables.product.prodname_github_codespaces %}
* {% data variables.product.prodname_copilot %}
* {% data variables.product.prodname_enterprise %}
* {% data variables.product.prodname_github_models %}
* {% data variables.product.prodname_registry %}
* {% data variables.large_files.product_name_long %}

{% data reusables.billing.actions-usage-delay %}

{% endif %}

## Key functionalities

With the new billing platform, you can:

* **Estimate spending:** Understand where your (annual, monthly, etc.) spending is trending based on the usage across {% ifversion ghec %}cost centers and {% endif %}budgets.
* **Gather insights and data:** Generate usage reports to share with your team or stakeholders, and know if you're on track with your budget.
{%- ifversion ghec %}
* **Charge business units:** Improve accountability by creating and assigning organizations, repositories, and members to cost centers.
{%- endif %}
* **Prevent overspending:** Use budgets and alerts to track and control your spending.
* **Observe and understand spending:** Understand how your spending changes over time and across which products.

## How do I access the new billing platform?

{% ifversion fpt %}

1. In the upper-right corner of any page on {% data variables.product.prodname_dotcom %}, select your profile photo.

   * For **personal accounts**, click **Settings**.
   * For **organizations**, click **Your organizations**, then next to the organization, click **Settings**.
1. In the left sidebar, click **Billing & Licensing**.

{% elsif ghec %}

{% data reusables.enterprise-accounts.access-enterprise %}
1. {% ifversion horizontal-nav %}At the top of the page,{% else %}In the enterprise account sidebar,{% endif %} click **{% octicon "credit-card" aria-hidden="true" aria-label="credit-card" %} Billing & Licensing**.

{% endif %}

If you have questions, please contact {% data variables.contact.contact_support_page %}.
