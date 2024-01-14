 ### Continue Infrastructure Automation with Terraform



 Let us continue from where we stopped in Project 16.

Based on our knowledge from the previous project, we can continue creating AWS resources!



#### Networking


##### Private subnets & best practices



Create 4 private subnets keeping in mind the following principles:


    Make sure you use variables or length() function to determine the number of AZs.
    
    
    Use variables and cidrsubnet() function to allocate vpc_cidr for subnets.
    
    
    Keep variables and resources in separate files for better code structure and readability.

    
    Tag all the resources you have created so far. Explore how to use format() and count functions to automatically tag subnets with its respective number.





##### A little bit more about Tagging



Tagging is a straightforward but very powerful concept that helps you manage your resources more efficiently:

    Resources are better organized in 'virtual' groups.

    
    They can be easily filtered and searched from console or programmatically.

    
    Billing team can easily generate reports and determine how much each part of infrastructure costs.(by department, by type, by environment, etc.)

    
    You can easily determine resources that are not being used and take actions accordingly.

    
    If there are different teams in the organisation using the same account, tagging can help differentiate who owns what resources.






