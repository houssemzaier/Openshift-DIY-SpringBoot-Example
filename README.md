it uses Java8 SpringBoot Maven


The OpenShift `diy` cartridge documentation can be found at:

http://openshift.github.io/documentation/oo_cartridge_guide.html#diy
=======
# Openshift-DIY-SpringBoot-Example
 



<h2>after cloning the project, you should do:</h2>
<ul>
  <li>On Windows run:   git update-index --chmod=+x .openshift/action_hooks/build</li>
  <li>On Windows run:   git update-index --chmod=+x .openshift/mvn</li>
 </hr> 
  <li>On Linux/OSX run: chmod +x .openshift/action_hooks/build</li>
  <li>On Linux/OSX run: chmod +x .openshift/mvn</li>
</ul>  
<p>then: > git commit -am "start the project"</p>
<p>finally: > git push </p>
