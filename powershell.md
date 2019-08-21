

# Get process with open port
* Get-Process -Id (Get-NetTCPConnection -LocalPort 6000).OwningProcess

# Stop process with port
* Stop-Process -Id (Get-Process -Id (Get-NetTCPConnection -LocalPort 6000).OwningProcess).Id
