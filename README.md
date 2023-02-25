# The tools

- There are multiple tools out there that can help you create and manage virtual environments (notice that we use the term “virtual environment” here, as such environemnt is not necessarily a VM. Technologies using containerization allow one to manage virtual environments as well).

- We are using two tools at school: VirtualBox and Vagrant.



- VirtualBox is a Virtual Machine provider. The virtual machines themselves will be spawned using VirtualBox. VirtualBox is free and lightweight, which make it a perfect choice for us.



- Vagrant is a tool that sits on top of a VM provider. Again, we chose to use VirtualBox as a provider, but other providers exist out there and Vagrant offers the possibilty to use dfferent providers (More info here). Just like VirtualBox, we choose to use Vagrant because it is free, reliable and well maintained. Keep in mind that the purpose here is to use Virtual environments, and both VirtualBox and Vagrant are just means to achieve this purpose.

![]( )

# Alternatives

- As mentioned previously, using VirtualBox and Vagrant at school doesn’t mean that all companies are going to work exactly the same way. Different tools are used, as well as different development workflows. We want you to understand how important it is to isolate your development environment from any host machine, whether it’s your personal computer or one of the school’s computers.



- Here are some examples of other softwares out there that are widely used to manage virtual environments:



- The VMWare products

- VMWare is one of the biggest virtualization company in the industry.

- It is safe to say that their tools are among the most reliable.

- On the other hands, most of their tools come for a price.

# Docker

- Containerization is a very good and efficient alternative to VMs for development environments

- Containers are much more lightweight than VMs, thus much faster to start and stop.

- The inconvinience of containers is that they sit on top of your OS. Unlike virtual machines, they don’t emulate the hardware, but rather share your machine’s hardware. We won’t go into the details of how containerization works, but to keep it simple, that means that if you run MacOS, it is not possible to run a Linux or Windows container. (Docker makes it work using VMs).

# More info here

# Conclusion

- VirtualBox and Vagrant together allow you to manage and ship isolated development environments. Those isolated environments in the context of the school (and in the future, in the context of a company) allow you to match the environment we use to automatically check your work.

- Although both VirtualBox and Vagrant are widely used in the industry, it doesn’t mean it is the only means to achieve virtualization, and other tools exist with their pros and cons.
