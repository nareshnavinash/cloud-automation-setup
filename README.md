# cloud-automation-setup

To run web automation suites in the Jenkins, we need to ensure that the following items are preinstalled in the Linux & Jenkins server.

1. Need to have Ruby and RVM.
2. Need to have Bundler gem installed.
3. Need to have the required browsers in which automation suites are going to run. (eg., Chrome, Firefox, etc.,)
4. Need to have (Selenium) Drivers corresponding to the browsers. (When Selenium 4.0+ is released this drivers is need not to be installed separately, since it will have internal driver manager.)
5. Each Jenkins slave (where UI automation is running) should have minimum 2GB ram and minimum 2 core processor with 1.2GHZ processor.
6. Allure plugin to be added in Jenkins (For reporting purpose)


Installation Procedures: (may change over a period of time)

## Ruby: 2.5.3

https://www.ruby-lang.org/en/documentation/installation/

gem install bundler



## RVM:

https://rvm.io/rvm/install



## Browsers:

https://www.howtoforge.com/tutorial/ubuntu-latest-browsers-firefox-chromium-opera/



## Browser Drivers:

https://tecadmin.net/setup-selenium-chromedriver-on-ubuntu/



## Allure for jenkins:

https://www.wedoqa.com/2017/11/allure-integration-in-jenkins/



#Plugins for Jenkins

https://wiki.jenkins.io/display/JENKINS/Rebuild+Plugin

https://jenkins.io/doc/pipeline/steps/allure-jenkins-plugin/

