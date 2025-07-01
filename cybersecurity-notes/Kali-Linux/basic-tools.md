# Kali Linux Basic Tools

## Nmap
Nmap (Network Mapper) is a powerful open-source tool for network discovery and security auditing.

### Common Usage Commands
- **Basic Scan**: 
  ```
  nmap <target>
  ```
- **Scan a Range of IPs**: 
  ```
  nmap <start-IP>-<end-IP>
  ```
- **Service Version Detection**: 
  ```
  nmap -sV <target>
  ```

### Tips
- Use `-A` for aggressive scanning which includes OS detection, version detection, script scanning, and traceroute.
- Always ensure you have permission to scan the target network.

## Netcat
Netcat is a versatile networking tool used for reading from and writing to network connections using TCP or UDP.

### Common Usage Commands
- **Listen on a Port**: 
  ```
  nc -l -p <port>
  ```
- **Connect to a Remote Host**: 
  ```
  nc <hostname> <port>
  ```
- **Transfer Files**: 
  ```
  # On the receiving end
  nc -l -p <port> > received_file.txt
  # On the sending end
  nc <hostname> <port> < file_to_send.txt
  ```

### Tips
- Netcat can be used for banner grabbing and as a simple chat tool.
- Use `-v` for verbose output to see more details about the connection.

## Metasploit
Metasploit is a penetration testing framework that helps security professionals find and exploit vulnerabilities.

### Common Usage Commands
- **Start Metasploit Console**: 
  ```
  msfconsole
  ```
- **Search for Exploits**: 
  ```
  search <exploit-name>
  ```
- **Use an Exploit**: 
  ```
  use <exploit-path>
  ```

### Tips
- Familiarize yourself with the various modules available in Metasploit.
- Always test exploits in a controlled environment to avoid unintended consequences.

## Wireshark
Wireshark is a network protocol analyzer that allows you to capture and interactively browse traffic on a computer network.

### Common Usage Commands
- **Start Capturing**: 
  ```
  wireshark
  ```
- **Capture on a Specific Interface**: 
  ```
  wireshark -i <interface>
  ```

### Tips
- Use display filters to focus on specific traffic types.
- Analyze captured packets to understand network behavior and troubleshoot issues.