## How to start azure pipeline

 1. Move into:
> develop

 1. Run:<br>
  	`mvn --batch-mode release:clean release:prepare`<br>
 	`git checkout -b tmp/${version} starter-parent-${version}` <br>
 	`git push --set-upstream origin tmp/${version}`
 	
 2. Merge **tmp/${version}** into **master**