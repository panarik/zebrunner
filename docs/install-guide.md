# Installation Guide

## Initial setup

1. Clone [Zebrunner](https://github.com/zebrunner/zebrunner) recursive and launch setup procedure
  ```
  git clone --recurse-submodule https://github.com/zebrunner/zebrunner.git && cd zebrunner && ./zebrunner.sh setup
  ```
  > Provide required details to finish configuration

2. Start services<br>
  ```
  ./zebrunner.sh start
  ```
  > If services need to be started after setup
  
3. After startup, the following components are available:
  > Use your host domain address or IP.  
  
| Components          	| URL                                                                                                    	   |
|---------------------	|----------------------------------------------------------------------------------------------------------	   |
| Zebrunner Reporting  	| [http://demo.qaprosoft.com](http://demo.qaprosoft.com)                                                 	   |
| Jenkins             	| [http://demo.qaprosoft.com/jenkins](http://demo.qaprosoft.com/jenkins)                                 	   |
| SonarQube           	| [http://demo.qaprosoft.com/sonarqube](http://demo.qaprosoft.com/sonarqube)                             	   |
| Web Selenium Hub    	| [http://demo:demo@demo.qaprosoft.com/selenoid/wd/hub](http://demo:demo@demo.qaprosoft.com/selenoid/wd/hub)       |
| Mobile Selenium Hub 	| [http://demo:demo@demo.qaprosoft.com/mcloud/wd/hub](http://demo:demo@demo.qaprosoft.com/mcloud/wd/hub) 	   |
| Mobile SmartTest Farm	| [http://demo.qaprosoft.com/stf](http://demo.qaprosoft.com/stf)                                         	   |

> admin/changeit crendetials should be used for Reporting and Jenkins, admin/admin for SonarQube.

## Support Channel

* Join [Telegram channel](https://t.me/zebrunner) in case of any question
