terraform state list =
used to see all the resources which are created by terraform

terraform state show <"resourse name"> =
used to see all the details of a particular resources

terraform refresh =
this can be used to see all the outputs mentioned in the main.tf file without running terraform apply and creating all the resources

terraform destroy -target <"target name"> =
this can be used to destroy a particular resource like if we want to destroy a particular ec2 instance from the whole infrastucture

terraform apply -target <"target name"> =
this can be used to create a particular resource like if we want to create a particular ec2 instance from the whole infrastucture

we can set variables to tarraform.tfvar file as well for reference watch
https://www.youtube.com/watch?v=SLB_c_ayRMo&t=6998s
