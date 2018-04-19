<p align="center">
    <h1 align="center">Yii 2 Basic Template with Jenkins</h1>
    <br>
</p>

Yii2 Jenkins is Yii2 Basic Project Template skeleton [Yii 2](http://www.yiiframework.com/) application with jenkins build configured.

Configuration
------------
Change your db configuration in config/db.php, config/test_db.php

Install your jenkins

Create a job template as shown in the link
http://jenkins-php.org/integration.html

Create your new buid job using this template.

In configuration change these values

Build 
    Invoke Ant
	Targets : build-parallel

    Report Crap
	XML Crap Report filename pattern : tests/_output/crap4j.xml

    PHPUnit-3.x (default)
 	PHPUnit-3.x (default) Pattern : tests/_output/report.xml
	
