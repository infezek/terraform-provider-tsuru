---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "tsuru_job_deploy Resource - terraform-provider-tsuru"
subcategory: ""
description: |-
  Perform an job deploy. Currently, only supporting deploys via prebuilt container images; in order to deploy via tsuru platforms please use tsuru-client
---

# tsuru_job_deploy (Resource)

Perform an job deploy. Currently, only supporting deploys via prebuilt container images; in order to deploy via tsuru platforms please use tsuru-client



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `image` (String) Docker Image
- `job` (String) Job name

### Optional

- `timeouts` (Block, Optional) (see [below for nested schema](#nestedblock--timeouts))
- `wait` (Boolean) Wait for the rollout of deploy

### Read-Only

- `id` (String) The ID of this resource.
- `output_image` (String) Image generated after success of deploy
- `status` (String) After apply may be three kinds of statuses: running or failed or finished

<a id="nestedblock--timeouts"></a>
### Nested Schema for `timeouts`

Optional:

- `create` (String)
- `delete` (String)
- `update` (String)