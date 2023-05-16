# Hash_Repo_Tool
This tool is a Python-based utility that converts any type of hash into MD5 and retrieves the reputation score of the hash from VirusTotal API. The Hash Converter and Reputation Checker Tool is a handy solution for malware analysts, security researchers, and other professionals who work with hashes regularly. The tool streamlines the process of conversion by simple user interface allows users to input a list of hashes in various formats, such as SHA1, SHA256, and others into an excel file and user just have to put their API Key of Virustotal, and get the corresponding MD5 hash and its reputation score from VirusTotal. The tool then stores this information in a convenient Excel file that can be used for further analysis and reporting. Overall, the Hash Converter and Reputation Checker Tool is a must-have for anyone working with hashes and looking to automate their workflow.
# Steps to Run the Tool : 
1. Download the zip file named "Hash_Repo" and extract it anywhere in your windows system
2. Under zip, you may find below mentioned files :
  * Hash_Repo.exe : Main executable file with GUI containing input fields and will give the desire output
  * Hash_File.xlxs : An excel file in which user will provide the has values and after successful running of Hash_Repo.exe, will provide output for the same. 
  * Readme : Description File
  * License : GNU License for the exe usage
3. As this exe file shows Virustotal results, user need to have VirusTotal API. Steps to get API key are as follows :
  * Go to the VirusTotal website at https://www.virustotal.com/.
  * Sign up for an account by clicking on the "Sign in" button at the top-right corner of the page and then clicking on the "Create an account" link.
  * After creating your account, log in to VirusTotal and navigate to the "API" tab.
  * Under the "API Key" section, click on the "Get your API key" button.
  * Follow the instructions provided to generate your API key.     
  * Once you have generated your API key, copy it and keep it in a secure location as you will need it to use the VirusTotal API in your scripts or applications.
  
  
  Note: There are both free and paid plans available for using the VirusTotal API, and the process for obtaining an API key may vary slightly depending on the plan         you choose. 

4. Firsty, open the excel file "Hash_File.xlxs" and put your hashes into the mentioned Hash Columns as shown in screenshot and then save and close it.

5. Now run the downloaded exe "Hash_Repo.exe", provide your Virustotal Auth Key and File path (where Hash_File.xlxs is stored) and click on the Calculate Button. Wait for result to load and then it will show some pop up message of completion. 

6. Check the file and user will get the desire result of the MD5 hashes with their reputation. Also, incase of any error it will directly pop up out with error notification.


# Note : Updated version contains : 
1. Added TR-ID which is a utility to identify file types from their binary signatures. 
2. Add IBM Xforce API result for the Hashes.
 
  
