# config-files

The HTTP service has resources in the following form:

/{application}/{profile}[/{label}]<br/>
/{application}-{profile}.yml<br/>
/{label}/{application}-{profile}.yml<br/>
/{application}-{profile}.properties<br/>
/{label}/{application}-{profile}.properties<br/>

For example:

curl localhost:8888/foo/development<br/>
curl localhost:8888/foo/development/master<br/>
curl localhost:8888/foo/development,db/master<br/>
curl localhost:8888/foo-development.yml<br/>
curl localhost:8888/foo-db.properties<br/>
curl localhost:8888/master/foo-db.properties<br/>


* Config Samples
  - myclient-test.properties
  - myclient-test2.yml
      
* Development
  - myapp-dev.properties
  
* Testing
  - myapp-test.properties

* Production
  - myapp-prd.properties
