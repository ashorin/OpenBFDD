<p>git clone git@github.com:ashorin/OpenBFDD.git openbfdd-0.5.3</p>
<p>cd openbfdd-0.5.3</p>
<p>git checkout debianize</p>
<p>./autogen.sh</p>
<p>./configure</p>
<p>git buildpackage --git-ignore-new --git-no-create-orig --git-debian-branch=debianize --git-upstream-branch=master -b</p>
<p>dput hh-precise ../openbfdd_0.5.3-5_amd64.changes</p>
