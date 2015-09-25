# TestCinderAPImicroversions
Patches and tests for cinder-api-microversions

Scott D'Angelo
openstack IRC: scottda
scott.dangelo@hp.com

Pull the patch for this review:
https://review.openstack.org/#/c/224910/


Patch in this code:
https://github.com/scottdangelo/TestCinderAPImicroversions/blob/master/testVersionDecorator

Addition of new /v3 api requires a new copy of etc/cinder/api-paste.ini:
cp etc/cinder/api-paste.ini /etc/cinder/api-paste.ini
