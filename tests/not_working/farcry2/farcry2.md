Far Cry 2

Tested on build from May 20th 2019

Launch options used (if any):
From git bash:
export DXVK_HUD=1
export DXVK_LOG_LEVEL=none
./FarCry2.exe

Symptoms:
Crashes on splashscreen

Remarks:
See log
Tried to apitrace, it didn't seem to save anywhere?
$ ./FarCry2.exe
apitrace: loaded into C:\Program Files (x86)\Steam\steamapps\common\Far Cry 2\bin\FarCry2.exe
apitrace: tracing to C:\Users\Tedster\Desktop\FarCry2.trace
This platform has logs enabled.  Don't use it for shipping.
This platform has traces enabled.  Don't use it for shipping.
(Info) Tracking create with access key = Sas85%$5
(Info) Tracking::Initialize without address, port, service Id
(Warning) OnlineConfigClient module not initialized
(Error) OnlineConfig was not initialized or the OnlineConfig ID is not valid.
(Warning) A long delay has been observed between two calls to Scheduler::Dispatch (7643 ms)
(Error) SandboxURL parameter not found
(Error) SandboxURL parameter not found
(Error) SandboxURL parameter not found
(Error) SandboxURL parameter not found
(Error) SandboxURL parameter not found
(Error) SandboxURL parameter not found
(Error) SandboxURL parameter not found
(Warning) A long delay has been observed between two calls to Scheduler::Dispatch (4757 ms)
(Error) SandboxURL parameter not found
(Error) SandboxURL parameter not found
(Error) SandboxURL parameter not found
apitrace: warning: caught exception 0xc0000005
apitrace: flushing trace
