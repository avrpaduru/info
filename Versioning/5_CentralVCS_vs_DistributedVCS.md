**Drawbacks of Central VCS:**

A centralized VCS has a single point of failure, which is the remote central VCS instance. If this instance is lost, it can cause productivity and data loss, and it will need to be replaced with another copy of the source code. If it temporarily becomes unavailable, it will prevent developers from pushing, merging or rolling-back code.

**Advantages of Distributed VCS:**

A distributed model architecture avoids the above pitfalls by keeping a full copy of the source code at each VCS instance. If any of the previously mentioned centralized failure scenarios happen within the distributed model, a new VCS instance can be swapped in to lead development mitigating any serious drop in productivity.

**<span style="color:Gray">References:**</span>
https://bitbucket.org/product/version-control-software
