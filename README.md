# Starter Terraform Alicloud Module

A starter/guide terraform module to facilitate module creation based on Terraform guidelines.

```hcl
provider "alicloud" {}

module "name_of_module" {
  // How to use it
}
```

## Module creation
- README (english)
- README-ZH (chinese)
- Module Code
- Complete Terratest test under `/test`
- Example under `/examples`
- Preferred a high volume of API calls with full test coverage


## References
- https://www.terraform.io/docs/registry/modules/publish.html
- https://www.terraform.io/docs/modules/index.html#standard-module-structure
- https://github.com/terraform-alicloud-modules
- https://github.com/terraform-alicloud-modules/terraform-alicloud-demo
- https://github.com/terraform-alicloud-modules/terraform-alicloud-classic-load-balance
