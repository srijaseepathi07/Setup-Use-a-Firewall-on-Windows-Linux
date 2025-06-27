# Setup-Use-a-Firewall-on-Windows-Linux
Configure and test basic firewall rules to allow or block traffic.
Open windows defendere firewall with advanced security in windows. 
Select Inbound rules. 
Right click on the Inbound rules then we should add new rule to Inbound rules.
Select port.
Specify local port number as 23 then block all the connections.
Select Domain ,Public, Private .
Give the name as Telnet.
Then open command promt as administration.
And give the command dism /online /Enable-Feature /FeatureName:TelnetClient
Then we get Image version and output as The Operation completed successfully.
And the other command telnet localhost 23 
Then it gives output and connect failed
Go over again windows defendere firewall with advanced security.
Go to Inbound rules and delete the telnet.
