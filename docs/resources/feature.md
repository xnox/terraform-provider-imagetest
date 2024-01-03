---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "imagetest_feature Resource - terraform-provider-imagetest"
subcategory: ""
description: |-
  Example resource
---

# imagetest_feature (Resource)

Example resource



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `name` (String) The name of the feature

### Optional

- `after` (Attributes List) Actions to run againast the harness after the core steps have run OR after a step has failed. (see [below for nested schema](#nestedatt--after))
- `before` (Attributes List) Actions to run against the harness before the core feature steps. (see [below for nested schema](#nestedatt--before))
- `description` (String) A descriptor of the feature
- `harness` (String) The ID of the test harness to use for the feature
- `labels` (Map of String) A set of labels used to optionally filter execution of the feature
- `steps` (Attributes List) Actions to run against the harness. (see [below for nested schema](#nestedatt--steps))

### Read-Only

- `id` (String) The ID of this resource.

<a id="nestedatt--after"></a>
### Nested Schema for `after`

Required:

- `cmd` (String)

Optional:

- `name` (String)


<a id="nestedatt--before"></a>
### Nested Schema for `before`

Required:

- `cmd` (String)

Optional:

- `name` (String)


<a id="nestedatt--steps"></a>
### Nested Schema for `steps`

Required:

- `cmd` (String)

Optional:

- `name` (String)