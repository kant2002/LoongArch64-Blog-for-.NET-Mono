

NOTE: To decrease the size of git repository, it will be pushed by force!!!

-------------2022.8.9
There are two packages for the  CoreRoot which both compiled based on
the commit b8ffae56d3269050ec84551fad44835536deffb3
within the https://github.com/dotnet/runtime/

* Linux.loongarch64.Debug0809.tar.xz
* Linux.loongarch64.Release0809.tar.xz

-------------2022.8.2  
There are two packages for the  CoreRoot which both compiled based on  
the commit bb178a843456b5febb810f5246454108c3020f67 and merged #73205 and #72572  
within the https://github.com/dotnet/runtime/

* Linux.loongarch64.Debug0802.tar.xz
* Linux.loongarch64.Release0802.tar.xz


**NOTE:**
This CoreRoot doesn't contain the coreclr's native part.
But you can compile the coreclr liking the command
<pre>
qiao@loongson-pc:~/work_qiao/push_runtime/src/coreclr$ ./build-runtime.sh -debug  -loongarch64 -nopgooptimize -skipmanaged
</pre>
