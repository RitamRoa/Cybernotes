# Moniker Links 

### Jargons and history
    
      CVE - common vulnerabilities and exposures
   #### Case Study of CVE-2024-21413  
          The vulnerability bypasses Outlook's security mechanisms when handing a specific type of hyperlink known as a Moniker Link.
          An attacker can abuse this by sending an email that contains a malicious Moniker Link to a victim, resulting in Outlook sending the user's NTLM credentials to the attacker once the hyperlink is clicked.
       NTLM : WWindows New Technology LAN Manager is a micrsoft based where the attccker will send "Moniker Link" from there the outlook will send the attacker a link of the users credentials.
       
       So basically: 
          -> Outlook can be used embed html code in emails but in micrsoft 360 etc what the attacker could do is that, they would send a hyperlink where <a href ="...!"> click me </a>
              that "!" would give the attcker the users credentials 
     SMTP : SImple mail transfer protocol: THrough server - to - server transfer of mails. 
     https://msrc.microsoft.com/update-guide/en-US/vulnerability/CVE-2024-21413
