
 𝚔𝚊𝚋𝚘𝚘𝚖 𝚟𝟷.0.0 𝚋𝚢 @𝚕𝚎𝚟𝚒𝚊𝚝𝚑𝚊𝚗𝟹𝟼

![Release](https://img.shields.io/badge/release-stable%201.0.0-green.svg)
![Language](https://img.shields.io/badge/made%20with-bash-brightgreen.svg)
![License](https://img.shields.io/badge/license-GPLv3-blue.svg)
![TestedOn](https://img.shields.io/badge/tested%20on-Kali%20Linux-red.svg)

<p align="center"><img src="https://static.dribbble.com/users/948184/screenshots/5611449/431_bob_omb_db.gif" width="100%"</p>

# 𝐤𝐚𝐛𝐨𝐨𝐦-̷𝐀̷ℙ𝚃: 𝐀𝐝𝐯𝐚𝐧𝐜𝐞𝐝 𝐏𝐞𝐧𝐭𝐫𝐚𝐭𝐢𝐨𝐧 𝐓𝐞𝐜𝐡𝐧𝐨𝐥𝐨𝐠𝐲 '<i>𝚙𝚎𝚗/𝚝𝚎𝚌𝚑</i>'

In the ever-evolving landscape of cybersecurity, the need for robust penetration testing tools is paramount. Introducing Kaboom-APT, a powerful and versatile automaton designed to revolutionize the way penetration testing is conducted. With a comprehensive set of features focused on information gathering and vulnerability assessment, Kaboom-APT stands as a testament to efficient and effective testing methodologies. Embrace Kaboom-APT's features to enhance your penetration testing journey. Whether you're customizing, exploring, or automating, Kaboom-APT is your partner in fortifying cybersecurity.


    kaboom --help

### 𝐔𝐧𝐥𝐞𝐚𝐬𝐡𝐢𝐧𝐠 𝐭𝐡𝐞 𝐏𝐨𝐰𝐞𝐫 𝐨𝐟 𝐊𝐚𝐛𝐨𝐨𝐦-𝐀𝐏𝐓
-----------------------------------

Kaboom-APT, short for "Advanced Penetration Testing," is an intelligent and automated solution meticulously crafted to simplify the complexities of penetration testing. Its purpose is clear: to equip security professionals with an advanced tool that seamlessly integrates into their workflow, enhancing their capabilities and efficiency.

### 𝐄𝐥𝐞𝐯𝐚𝐭𝐢𝐧𝐠 𝐘𝐨𝐮𝐫 𝐓𝐞𝐬𝐭𝐢𝐧𝐠 𝐏𝐡𝐚𝐬𝐞𝐬
------------------------------

At its core, Kaboom is a multi-faceted tool that excels in two fundamental phases of penetration testing: information gathering and vulnerability assessment. This automated powerhouse streamlines the process, allowing testers to focus on analyzing results rather than grappling with manual tasks.

### 𝙸𝚗𝚏𝚘𝚛𝚖𝚊𝚝𝚒𝚘𝚗 𝙶𝚊𝚝𝚑𝚎𝚛𝚒𝚗𝚐

Kaboom efficiently conducts comprehensive information gathering through the following methods:

- Port Scanning: Leveraging the power of Nmap, Kaboom-APT scans ports to identify potential entry points, offering insights into the network's structure.

- Web Resources Enumeration: Through Dirb, Kaboom-APT identifies and catalogs web resources, providing a thorough understanding of the target's online presence.

### 𝐕𝐮𝐥𝐧𝐞𝐫𝐚𝐛𝐢𝐥𝐢𝐭𝐲 𝐀𝐬𝐬𝐞𝐬𝐬𝐦𝐞𝐧𝐭


Kaboom empowers testers to perform thorough vulnerability assessments, enabling them to uncover potential weaknesses:

- Web Vulnerability Assessment: By utilizing tools such as Nikto and Dirb, Kaboom-APT identifies vulnerabilities in web applications, ensuring they meet the highest security standards.

- Automatic Vulnerabilities Research: Kaboom-APT automatically integrates with Searchsploit and Metasploit, streamlining the process of identifying and mitigating vulnerabilities.

- Dictionary Attacks: Employing Hydra, Kaboom-APT conducts dictionary attacks against open services, targeting common protocols such as SSH, POP3, IMAP, and RDP.

### 𝐒𝐢𝐦𝐩𝐥𝐢𝐟𝐢𝐞𝐝 𝐔𝐬𝐚𝐠𝐞

Kaboom-APT simplifies usage with both interactive and non-interactive modes:

- Interactive mode: Just type `kaboom` and hit [ENTER], and the script handles the rest.

- Non-interactive mode: Use the command `kaboom -t <target_ip> -f <report_path> [-p one_or_more_phases]` for specific targeting and reporting.

For Help


If you need assistance, run `kaboom -h` (or `kaboom --help`) to access the help menu and explore available options.

## 𝐂𝐮𝐬𝐭𝐨𝐦𝐢𝐳𝐢𝐧𝐠 𝐊𝐚𝐛𝐨𝐨𝐦-𝐀𝐏𝐓


To further tailor Kaboom to your needs, you can provide additional arguments and customize its behavior:

- Configuration Files: Kaboom-APT supports configuration files for fine-tuning its operation.

- Wordlists: Customize wordlists for dictionary attacks using Hydra and Dirb, enhancing attack efficiency.

- Output Customization: Personalize output file names and locations to match your preferences.

### 𝐄𝐧𝐡𝐚𝐧𝐜𝐢𝐧𝐠 𝐖𝐨𝐫𝐤𝐟𝐥𝐨𝐰 𝐰𝐢𝐭𝐡 𝐊𝐚𝐛𝐨𝐨𝐦-𝐀𝐏𝐓

Kaboom is more than just a tool; it's a comprehensive suite of capabilities designed to empower security professionals in their pursuit of robust cybersecurity. With its intelligent automation, streamlined workflows, and powerful features, Kaboom-APT marks a new era in penetration testing. Embrace the power of Kaboom and elevate your cybersecurity defenses.

- **Non-Interactive Mode**: For tailored testing, use the command `kaboom -t <target_ip> -f <report_path> [-p phases]` to customize the process according to your needs.

- 
		
		┌──(root㉿test-station)-[/home/user1/kaboom/kaboom]
		└─# ./kaboom.sh
		Insert hosts (example 192.168.1.1-5):
		>> 10.10.10.222
		Insert path where to save results (without final /):
		>> /home/user1/Documents
		choice the phases to perform [i=IG, v=VA, d=dictionary]:
		>> iv
		Shutdown pc at the end of script [YES/NO] (default NO):
		>> NO
		
		[*******************************************************]
		[***]START SCRIPT AT Thu Aug 17 06:55:51 PM MDT 2023[***]
		[*******************************************************]
		
		----------------------------------
		----------------------------------
		ITAREATION:   1
		TARGET:   10.10.10.222
		PROGRESS: [===================>]
		----------------------------------

		[PHASE:]starting IG...
	
	        [+] Network Mapper activated. Connection establishing...
	        [*]start Scanning the network...

		Starting Nmap 7.94 ( https://nmap.org ) at 2023-08-17 18:54 MDT
		Illegal character(s) in hostname -- replacing with '*'
		Illegal character(s) in hostname -- replacing with '*'
		Nmap scan report for http:**delivery.htb (10.10.10.222)
		Host is up (0.13s latency).
		
		PORT   STATE SERVICE
		22/tcp open  ssh
		| ssh-hostkey: 
		|   2048 9c:40:fa:85:9b:01:ac:ac:0e:bc:0c:19:51:8a:ee:27 (RSA)
		|   256 5a:0c:c0:3b:9b:76:55:2e:6e:c4:f4:b9:5d:76:17:09 (ECDSA)
		|_  256 b7:9d:f7:48:9d:a2:f2:76:30:fd:42:d3:35:3a:80:8c (ED25519)
		80/tcp open  http
		|_http-title: Welcome
		
		Nmap done: 1 IP address (1 host up) scanned in 5.06 seconds
		
		[PHASE:]starting VA...
		
		        [-]no exploits found!
		
		[*******************************************************]
		[***] END SCRIPT AT Thu Aug 17 06:54:39 PM MDT 2023 [***]
		[*******************************************************]
		                                                              
## 𝐄𝐦𝐩𝐨𝐰𝐞𝐫𝐢𝐧𝐠 𝐂𝐮𝐬𝐭𝐨𝐦𝐢𝐳𝐚𝐭𝐢𝐨𝐧
Kaboom empowers you to customize its behavior by adjusting variables at the script's outset. This allows you to tailor the tool to your specific requirements, whether it's selecting wordlists for Hydra and Dirb, specifying a Metasploit scan script, or refining output file names.

## 𝐄𝐦𝐛𝐫𝐚𝐜𝐞 𝐭𝐡𝐞 𝐅𝐮𝐭𝐮𝐫𝐞 𝐨𝐟 𝐏𝐞𝐧𝐞𝐭𝐫𝐚𝐭𝐢𝐨𝐧 𝐓𝐞𝐬𝐭𝐢𝐧𝐠

Kaboom ushers in a new era of penetration testing, where automation, efficiency, and precision converge to yield unparalleled results. With its advanced features and user-friendly interface, Kaboom-APT is your ally in fortifying digital landscapes against potential threats. Experience the power of Kaboom and elevate your penetration testing game today.

```bash
#KABOOM_PATH=''		# THE PATH COULD BE SET HERE INSTEAD OF IN BASHRC FILE

if [[ "$KABOOM_PATH" == '' ]]; then
	KABOOM_PATH='.'
fi

# USER WORDLISTS
USERLIST_HYDRA_SSH="$KABOOM_PATH/user_wordlist_short.txt"
USERLIST_HYDRA_POP3="$KABOOM_PATH/user_wordlist_short.txt"
USERLIST_HYDRA_IMAP="$KABOOM_PATH/user_wordlist_short.txt"
USERLIST_HYDRA_RDP="$KABOOM_PATH/user_wordlist_short.txt"
USERLIST_HYDRA_SMB="$KABOOM_PATH/user_wordlist_short.txt"

# PASSWORD WORDLISTS
PASSLIST_HYDRA="$KABOOM_PATH/fasttrack.txt"
PASSLIST_HYDRA_SSH="$PASSLIST_HYDRA"
PASSLIST_HYDRA_POP3="$PASSLIST_HYDRA"
PASSLIST_HYDRA_IMAP="$PASSLIST_HYDRA"
PASSLIST_HYDRA_RDP="$PASSLIST_HYDRA"
PASSLIST_HYDRA_SMB="$PASSLIST_HYDRA"

# DIRB WORDLISTS
HTTP_WORDLIST="$KABOOM_PATH/custom_url_wordlist.txt"
HTTP_EXTENSIONS_FILE="$KABOOM_PATH/custom_extensions_common.txt"

# METASPLOIT SCAN SCRIPT
METASPLOIT_SCAN_SCRIPT='./metasploit_scan_script'

# NMAP FILES
SCRIPT_SYN='script-syn'
UDP='udp'
SYN='syn'
```

# 𝐀𝐝𝐯𝐚𝐧𝐜𝐞𝐝 𝐏𝐞𝐧𝐞𝐭𝐫𝐚𝐭𝐢𝐨𝐧 𝚃𝚎𝚌𝚑𝚗𝚘𝚕𝚘𝚐𝚢

## 𝐒𝐭𝐫𝐞𝐚𝐦𝐥𝐢𝐧𝐢𝐧𝐠 𝐭𝐡𝐞 𝐏𝐞𝐧𝐞𝐭𝐫𝐚𝐭𝐢𝐨𝐧 𝐓𝐞𝐬𝐭𝐢𝐧𝐠 𝐏𝐫𝐨𝐜𝐞𝐬𝐬
Kaboom's significance extends beyond its individual capabilities; it offers a holistic approach that streamlines the entire penetration testing process. Its integration of various tools and techniques into a cohesive framework minimizes the complexities often associated with cybersecurity assessments. This streamlined workflow empowers security professionals to focus on analysis and action, rather than grappling with disparate tools and fragmented processes. In an era where cybersecurity is paramount, Kaboom emerges as a pivotal player in the ongoing battle to secure digital assets. Its comprehensive suite of capabilities, meticulous engineering, and holistic approach set it apart as a tool that empowers security professionals to proactively safeguard against cyber threats. As the digital landscape continues to evolve, Kaboom-APT stands as a beacon of innovation, helping to fortify the digital world against the ever-persistent forces of cybercrime.

---

 # 𝐊𝐚𝐛𝐨𝐨𝐦 𝐄𝐧𝐡𝐚𝐧𝐜𝐢𝐧𝐠 𝐂𝐲𝐛𝐞𝐫𝐬𝐞𝐜𝐮𝐫𝐢𝐭𝐲 𝐀𝐫𝐬𝐞𝐧𝐚𝐥 
 ## 𝐂𝐮𝐬𝐭𝐨𝐦𝐢𝐳𝐚𝐭𝐢𝐨𝐧: 𝐓𝐚𝐢𝐥𝐨𝐫𝐢𝐧𝐠 𝐭𝐨 𝐏𝐫𝐞𝐜𝐢𝐬𝐢𝐨𝐧

Kaboom recognizes that each engagement requires a unique approach. Customize the tool to your specific needs:

- Adjust variables for tailored wordlists and output filenames.

# 𝐄𝐱𝐚𝐦𝐩𝐥𝐞 𝐜𝐮𝐬𝐭𝐨𝐦𝐢𝐳𝐚𝐭𝐢𝐨𝐧𝐬

	HYDRA_WORDLIST="custom_hydra_wordlist.txt"
	DIRB_WORDLIST="custom_dirb_wordlist.txt"
  	OUTPUT_FILENAME="custom_report.txt"

    

Multifaceted Exploration: Multi-Target Specification

Efficiency matters in penetration testing. Kaboom-APT answers this need with multi-target specification:

Efficiently assess multiple targets by defining up to 254 hosts within a C-class network.

    	kaboom -t <target_ip> -f <report_path> -p one_or_more_phases

Elevating Interaction: The New CLI Interface

Interacting with Kaboom-APT is more intuitive than ever:

A revamped Command Line Interface (CLI) simplifies command entry and navigation.

	kaboom -t <target_ip> -f <report_path> -p one_or_more_phases

Precision in Discovery: Enhanced Nmap Scans

Kaboom-APT's Nmap scan functionality has transformed:

Detailed insights into open ports and services facilitate vulnerability identification.

	kaboom -t <target_ip> -f <report_path> -p nmap


Structured Clarity: Streamlined Directory Hierarchy

Managing data across multiple targets made easy:

An optimized directory hierarchy simplifies data organization and analysis.


	# Directory hierarchy
	/home/user1/Documents/kaboom/target1
	/home/user1/Documents/kaboom/target2


Automating Insights: Automatic Metasploit Research

Simplify association of Metasploit modules with CVE codes:

Automate exploit identification during vulnerability assessments.

 	 kaboom -t <target_ip> -f <report_path> -p metasploit

Widening the Scope: Non-Canonical Port Recognition

Modern networks harbor services on non-canonical ports:

Kaboom-APT's feature detects and assesses services on non-standard ports.

	kaboom -t <target_ip> -f <report_path> -p non_canonical_ports

### 𝐇𝐚𝐫𝐧𝐞𝐬𝐬𝐢𝐧𝐠 𝐂𝐫𝐞𝐝𝐞𝐧𝐭𝐢𝐚𝐥𝐬: 𝐄𝐟𝐟𝐢𝐜𝐢𝐞𝐧𝐭 𝐂𝐫𝐞𝐝𝐞𝐧𝐭𝐢𝐚𝐥𝐬 𝐌𝐚𝐧𝐚𝐠𝐞𝐦𝐞𝐧𝐭

Credentials uncovered during dictionary attacks are a goldmine of information. Kaboom recognizes the significance of this data and introduces a feature that allows testers to retrieve, print, and save credentials. This management feature ensures critical information is easily accessible for in-depth analysis and comprehensive reporting.

### 𝐓𝐰𝐢𝐧 𝐁𝐫𝐨𝐭𝐡𝐞𝐫 - 𝐓𝐫𝐢𝐠𝐦𝐚𝐩: 𝐀 𝐏𝐚𝐫𝐚𝐥𝐥𝐞𝐥 𝐄𝐧𝐝𝐞𝐚𝐯𝐨𝐫
As Kaboom evolved, a parallel project named Trigmap (Trigger Nmap) emerged. Trigmap shares similar objectives with Kaboom-APT but adopts a distinct approach. This sibling tool relies exclusively on Nmap to execute its tasks. The synergy between Kaboom-APT and Trigmap enriches penetration testing endeavors, offering a comprehensive toolkit for varying scenarios.

To delve deeper into Trigmap's capabilities, visit the Trigmap repository.

### 𝑬𝒕𝒉𝒊𝒄𝒂𝒍 𝑹𝒆𝒔𝒑𝒐𝒏𝒔𝒊𝒃𝒊𝒍𝒊𝒕𝒚: 𝑻𝒉𝒆 𝑲𝒂𝒃𝒐𝒐𝒎-𝑨𝑷𝑻 𝑫𝒊𝒔𝒄𝒍𝒂𝒊𝒎𝒆𝒓

Kaboom-APT is a tool of empowerment, carefully crafted for cybersecurity professionals striving to enhance their capabilities. While the potential it holds is awe-inspiring, it comes hand in hand with a profound responsibility. As you embark on your journey with Kaboom-APT, we emphasize the need for ethical conduct, responsible use, and a steadfast commitment to upholding the principles of cybersecurity.

<p align="center"><img src="https://github.com/Leviathan36/kaboom/blob/master/kaboom_images/logo.png" width="100%" height="auto">

![Build and Deploy](https://github.com/kratostaine/spring-authorization-server/actions/workflows/continuous-integration-workflow.yml/badge.svg)
