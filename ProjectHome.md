uuid implemented in as3. being a pure actionscript library it can be used for any Flash/Flex/AIR project.

## usage ##
  1. download and unzip.
  1. place asuuid.swc file to your project/src/libs directory.
  1. import this lib
```
import com.laiyonghao.Uuid;
```
## example ##
  * code
```
for(var j:int = 0; j < 10; ++j){
	var uuid:Uuid = new Uuid();
	trace(uuid);
}
```
  * output
```
7C00F09D-7CF8-81D2-419D-A27241630344
7C0060AD-7CF8-81FD-41D4-50718B8D61FE
7C0180AD-7CF8-81FD-41DC-BF1BBE3A7690
7C01C0AD-7CF8-81FD-41DD-0293928D63E0
7C0100AD-7CF8-81FD-41DE-8D64326D1C6B
7C0140AD-7CF8-81FD-41DD-4AFBBB2A816E
7C02B0AD-7CF8-81FC-41D1-C315291F7DDF
7C02F0AD-7CF8-81FC-41DD-32DEA97B2FA6
7C0240AD-7CF8-81FC-41DC-EFD0340974F4
7C0390AD-7CF8-81FC-41B7-6B87769D02C5
```