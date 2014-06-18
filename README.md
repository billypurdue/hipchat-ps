#hipchat-ps
The hipchat-ps module is inspired by HipChat's [hipchat-cli](https://github.com/hipchat/hipchat-cli) but wraps up the functionality to send a HipChat message in an easy to use Windows PowerShell module. 
I forked the original project and have done my best to add a bit more to it, and to clean it up a bit (not that what it had before was bad, I'm a novice and appreciate a lot of white space to seperate things out).

## Getting Started
1. Copy this module to any location found in $env:PSModulePath

	Copy to Windows directory for global install:
	
	```
	C:\Windows\System32\WindowsPowerShell\v1.0\Modules\Publish-HipChatRoomMessage\Publish-HipChatRoomMessage.psm1
	```

1. Import the module

	C:\PS>Import-Module Publish-HipChatRoomMessage
	
1. List available functions	

		C:\PS>Get-Command -Module Publish-HipChatRoomMessage
	
1. Get help on the module

		C:\PS>Get-Help Publish-HipChatRoomMessage -examples
	
		C:\PS>Get-Help Publish-HipChatRoomMessage -detailed
	
1. Execute the module

		C:\PS>Publish-HipChatRoomMessage -apitoken e6b4ed16569cb86d272692171d5 5c8 -roomid 49459 -from "lloyd" -message "Test Message http://www.google.com"		

## Disclaimer
NO warranty, expressed or written
