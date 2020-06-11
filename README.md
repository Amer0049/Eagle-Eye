# Eagle-Eye
Port Scanner for Pentesting
   
   "Installation"
   
git clone https://github.com/Amer0049/Eagle-Eye.git

cd Eagle-Eye

chmod +x Eagle-Eye
    
    
Usage: ./Eagle-Eye.sh 1.1.1.1 quick


Scan Types:

	Quick:	Shows all open ports quickly (~15 seconds)
	
	Basic:	Runs Quick Scan, then runs a more thorough scan on found ports (~5 minutes)
	
	UDP:	Runs "Basic" on UDP ports (~5 minutes)
	
	Full:	Runs a full range port scan, then runs a thorough scan on new ports (~5-10 minutes)
	
	Vulns:	Runs CVE scan and nmap Vulns scan on all found ports (~5-15 minutes)
	
	Recon:	Suggests recon commands, then prompts to automatically run them
	
	All:	Runs all the scans (~20-30 minutes)
   
  Note:  please do not use this tool for illegal purposes.
