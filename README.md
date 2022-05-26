## How to execute JMeter

prerequisites
- Azure account created
- az-cli installed and configured
- terraform installed

Deploy the application using using Terraform on Azure, on terraform-spring folder, execute
````sh
terraform init
terraform apply
````

Open JMeter software and open JMeter projects (.jmx) on the folder jmeter

It's possible to execute JMeter on terminal
````sh
./jmeter -n -t /home/joao/Sources/Test/jmeter-petclinic-tests/jmeter/queryPet.jmx -l /home/joao/Sources/Test/jmeter-petclinic-tests/jmeter/restBank.jtl -e -o /home/joao/Sources/Test/jmeter-petclinic-tests/jmeter/report
````