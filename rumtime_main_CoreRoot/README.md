

NOTE: To decrease the size of git repository, it will be pushed by force!!!

-------------2022.11.10  
There are two packages for the  CoreRoot which both compiled based on
the commit d71038af9b49acb72140c105c90b765e9338741b  
within the https://github.com/dotnet/runtime/

* Core_Root8.0_Debug1110.tar.xz
* Core_Root8.0_Release1110.tar.xz

**NOTE:**
This CoreRoot doesn't contain the coreclr's native part.
But you can compile the coreclr liking the command
<pre>
qiao@loongson-pc:~/work_qiao/push_runtime/src/coreclr$ ./build-runtime.sh -debug  -loongarch64 -nopgooptimize -skipmanaged
</pre>
