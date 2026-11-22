# Network Connections Analysis Using Netstat

## 1. Objective
To examine active network connections on a Windows system and understand local addresses, remote IP addresses, port numbers, and connection states.

## 2. Tools Used
- Windows 11
- Command Prompt
- `netstat` command

## 3. Commands Used

```cmd
netstat -ano
```

To display established connections:

```cmd
netstat -ano | findstr ESTABLISHED
```

## 4. Procedure
1. Opened Windows Command Prompt.
2. Executed the `netstat -ano` command.
3. Observed active network connections.
4. Examined local and foreign IP addresses.
5. Identified port numbers and connection states.
6. Observed Process IDs (PIDs) associated with network connections.

## 5. Observations
- Multiple active network connections were observed.
- Several connections used HTTPS-related remote port 443.
- Local and remote IP addresses were displayed.
- Different connection states were observed.
- Some entries showed listening ports.
- Process IDs were available for further process identification.

## 6. Security Relevance
Network connection monitoring helps security analysts understand communication between a computer and external systems.

Unexpected remote connections, unfamiliar ports, and unusual connection patterns may require further investigation.

A connection to an unfamiliar IP address does not automatically indicate malicious activity.

## 7. Conclusion
This exercise provided practical exposure to Windows network connection monitoring using the `netstat` command. It helped develop an understanding of IP addresses, ports, connection states, and process identification.

## 8. Learning Outcome
- Learned to inspect network connections.
- Understood local and foreign addresses.
- Identified network ports and connection states.
- Learned how Process IDs can help identify applications associated with network connections.
