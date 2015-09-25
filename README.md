# TestCinderAPImicroversions
Patches and tests for cinder-api-microversions

Scott D'Angelo
openstack IRC: scottda
scott.dangelo@hp.com

Pull the patch for this review:
https://review.openstack.org/#/c/224910/
git fetch https://review.openstack.org/openstack/cinder refs/changes/10/224910/3 && git checkout FETCH_HEAD

IMPORTANT!
in Devstack, you will need to copy /opt/stack/cinder/etc/cinder/api-paste.ini to /etc/cinder
if you do not, c-api will not start

Patch in this code:


