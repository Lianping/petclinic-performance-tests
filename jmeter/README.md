Pet Clinic Performance Test 
===========================
Mark Nolan, 8 Feb 2013


JMeter JMX file takes two command line parameters:
- "hostname": target machine to fire the URLs at, defaults to "localhost"
- "port": port number of target machine, defaults to "80"

Examples invokation:
- run JMeter against a taget host and port, (n)o GUI, using provided (t)est file

C:\apache-jmeter-2.9\bin>jmeter.bat -Jhostname=127.0.0.1 -Jport=8080 -n -t C:\jmeter\tests\PetClinicPerformanceTest.jmx -l petclinic.jtl