Pet Clinic Performance Test 
===========================
Mark Nolan, 7 Feb 2013


JMeter JMX file takes two command line parameters:
- "hostname": target machine to fire the URLs at, defaults to "localhost"
- "port": port number of target machine, defaults to "80"

Examples invokation:
- run JMeter against a taget host and port, (n)o GUI, using provided (t)est file

C:\apache-jmeter-2.9\bin>jmeter.bat -Jhostname=172.18.48.169 -Jport=8080 -n -t C:\tests\BuildPipeline\PetClinicPerformanceTest.jmx





