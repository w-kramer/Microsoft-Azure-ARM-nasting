# Nesting templates for Azure ARM deployments

Sometimes you need some nesting to do things right. E.g. when you deploy a virtual machine, you need to create the nic with a dynamic ip first and then update the ip to a static one. Otherwise you would need to know the next available ip in the first place.
