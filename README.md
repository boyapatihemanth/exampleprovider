## USAGE (local testing):

resource "example_server" "my-server-name" {
	uuid_count = "1"
}

terraform {
  required_providers {
    example = {
      version = "~> 1.0.0"
      source  = "terraform-example.com/exampleprovider/example"
    }
  }
}

Reference: https://www.infracloud.io/blogs/developing-terraform-custom-provider/
