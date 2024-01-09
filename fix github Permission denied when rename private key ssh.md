# Window
- create file "%USERPROFILE%\.ssh\config" & add text
```markdown
Host github.com
	HostName github.com
	IdentityFile <pathtofile-privatekeyssh>
```
# Linux
- Create file "~/.ssh/config" & add text
```markdown
Host github.com
	HostName github.com
	IdentityFile <pathtofile-privatekeyssh>
```

# Test 
- Run on terminal "ssh -T git@github.com"