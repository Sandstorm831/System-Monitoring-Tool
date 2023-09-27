# functions
func GetCurrentCpu(r chan float64); <br />
func GetProcs()  int; <br />
func GetHz()  uint; <br />
func GetHostName() string; <br />
func GetInterfaceNames() []string; <br /> 
func GetUptime() float64; <br />
func GetBytes(interfaceName string) Bytes; <br />
func GetMem() MemKB; <br />
func GetListOfPid() []string; <br />
func GetPidCpuAndUptime(pid string) (PidStat, error) </br>
func GetPidMem(pid string) uint64; </br>
func GetPidCommandLine(pid string) (string, error); </br>
func GetPidName(pid string) (string, error); </br>

The output csv of example.go:
//epoch, cpu, mUsed, sUsed, cache, uptimeInMin
