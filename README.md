# Cloudformation aka CFN

## Resources
- [Cloudformation](https://docs.aws.amazon.com/cloudformation/)
- [User Guide](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html)
- [Template sections](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-anatomy.html)
- [Intrinsic functions](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference.html)

## Commands
```bash
# https://github.com/czam01/cloudformation/tree/master
aws cloudformation validate-template --template-body file://template.yaml
aws cloudformation validate-template --output table|yaml|json --template-body file://template.yaml
```