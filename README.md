# tibco-rendezvous
rv pub/sub test

echo "# tibco-rendezvous" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/hwshin16/tibco-rendezvous.git
git push -u origin master


#Manually Installation GemFire Maven Reop Artifacts

	mvn install:install-file -Dfile=/devtools/repositories/IMDG/pivotal-gemfire-9.0.1/lib/geode-core-9.0.1.jar -DgroupId=io.pivotal.gemfire -DartifactId=geode-core -Dversion=9.0.1 -Dpackaging=jar
	
	
	mvn install:install-file -Dfile=/devtools/repositories/IMDG/pivotal-gemfire-9.0.1/lib/geode-wan-9.0.1.jar -DgroupId=io.pivotal.gemfire -DartifactId=geode-wan -Dversion=9.0.1 -Dpackaging=jar
	
	
	mvn install:install-file -Dfile=/devtools/repositories/IMDG/pivotal-gemfire-9.0.1/lib/geode-cq-9.0.1.jar -DgroupId=io.pivotal.gemfire -DartifactId=geode-cq -Dversion=9.0.1 -Dpackaging=jar