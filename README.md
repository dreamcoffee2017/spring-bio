# spring-bio

* spring-boot:1.0.0.RELEASE
* app controller sleep:1s
* tomcat bio max-threads:1
* jmeter users:100 thoughput:0.99
* jmc bio-acceptor num:1 status:RUNNABLE->WAITING->RUNNABLE
* bio-exec num:0->1 status:RUNNABLE->TIMED_WAITING->RUNNABLE

* tomcat bio max-threads:10
* jmeter users:100 thoughput:9.65
* jmc bio-acceptor num:1 status:RUNNABLE->WAITING->RUNNABLE
* bio-exec num:0->10 status:RUNNABLE->TIMED_WAITING->WAITING