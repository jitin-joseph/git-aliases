# git-aliases

for git bash
C:\Program Files\Git\etc\profile.d\aliases.sh

alias ga='ga'
alias gaa='git add .'
alias gcm='git commit'
alias gpl='git pull'
alias gps='git push'
alias gsw='git switch'
alias gch='git checkout'
alias gm='git merge'
alias gst='git status'


for Powershell
C:\Users\[Computer name]\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1

function GitAdd {git add}
New-Alias -Force -Name ga -Value GitAdd

function GitAddA {git add .}
New-Alias -Force -Name gaa -Value GitAddA

function GitCommit {git commit}
New-Alias -Force -Name gcom -Value GitCommit

function GitPull {git pull}
New-Alias -Force -Name gpl -Value GitPull

function GitPush {git push}
New-Alias -Force -Name gpush -Value GitPush

function GitSwitch {git switch}
New-Alias -Force -Name gsw -Value GitSwitch

function GitCheckout {git checkout}
New-Alias -Force -Name gch -Value GitCheckout

function GitMerge {git merge}
New-Alias -Force -Name gmr -Value GitMerge

function GitStatus {git status}
New-Alias -Force -Name gst -Value GitStatus


![image](https://user-images.githubusercontent.com/62872551/196407120-005b1572-11b1-4a88-802f-db77a6701986.png)

