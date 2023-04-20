# test

```hcl
  resource "example_resource_guidelines" "main" {
    depends_on = [
      example_resource_reference.main
    ]
    for_each   = var.map_to_loop
    provider   = provider-alias
    project    = var.project_id
    variable1  = "value1"         
  }
```
