![workflow](https://github.com/zablon-oigo/cfs-aws-security-challenge-with-terrafrom/actions/workflows/main.yml/badge.svg)

#### Architecture Diagram

![demo(1)](https://github.com/user-attachments/assets/55bc0eb1-2bdc-4b6a-a33e-4b2bd1fc5d16)



#### Description
In this project, I designed and implemented a scalable virtual private cloud architecture with public and private subnets spanning two availability zones for high availability. The architecture includes a NAT instance to securely provide outbound internet access for resources within the private subnets, while a load balancer ensures efficient distribution of incoming traffic across instances. Additionally, I integrated amazon cloudFront as a content delivery network with geo-restrictions, specifically limiting content access to Kenya, thereby ensuring low-latency and localized access for users.
#### Run Locally

Clone the project

```bash
  git clone https://github.com/zablon-oigo/cfs-aws-security-challenge-with-terraform.git
```

Go to the project directory

```bash
  cd cfs-aws-security-challenge-with-terraform
```

Install Plugins

```bash
  terraform init 
```

Preview Infrastructure Changes

```bash
  terraform plan
```
Apply the Configuration

```bash
  terraform apply
```
#### Blog
For more information, check out my [blog](https://medium.com/@zablon-oigo/enhancing-aws-security-a-guide-to-securing-your-infrastructure-with-terraform-7f3e230a524a)
#### Feedback
If you have any feedback, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/zablon-oigo/).
#### Acknowledgements
I would like to extend my sincere gratitude to **CloudForceSky community** for their invaluable support, **Marcrine** for the Docker images, and to **Kevin Tuei** for presenting this challenge, which provided a valuable opportunity for growth and learning.
