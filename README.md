# terraform-aws-regions

## How to use

1. Download `aws-regions.tf` into your own repository:
    ```bash 
    ...
    ```

2. Initialise Terraform:
   ```bash
   terraform init
   ```

3. Use aliases like so:
    ```hcl-terraform
    resource "aws_something" "something_in_sydney" {
      provider = aws.ap-southeast-2
      foo = "bar"
      baz = 42
      # ...
    }
    ```

## Source

- [AWS service endpoints](https://docs.aws.amazon.com/general/latest/gr/rande.html)

## License

Free to use, at your own risk; no warranties. ¯\\\_(ツ)_/¯
