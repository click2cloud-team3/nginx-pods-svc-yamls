# nginx-pods-svc-yamls
* These yaml files are tested in arktos + Mizar cni environment so firstly set up this environment<br>
* Each deployable pod is have its service yaml. <br>
* Test case having same namespaces and same app selector name will give expected output while in rest of cases system result will be "connection refused" due to either dissimilar namespace or dissimilar app selector name. <br>
* This test conclude that there is no conflicts of objects under different namespaces. <br>
