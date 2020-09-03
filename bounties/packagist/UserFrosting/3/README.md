## ✍️ Description
UserFrosting is following strict email verification but to bypass this use email change 
## 🕵️‍♂️ Proof of Concept 
1. setup UserFrosting repo or https://demo.userfrosting.com/ platform to reproduce the vulnerability
2. Create a user there is a strict email verification so verify the email to login
3. now go to My Account change the email id then save
4. It will saves the new email id without any verification
5. now logout and try login it wont allow us to login with old verified email but with new unverified email
## 💥 Impact
An attacker is able to register victims account without his knowledge.
Pre account takeover possibility
## ✅ Checklist
- [x] _Created and populated the README.md and vulnerability.json files_
- [x] _Provided the repository URL and any applicable [permalinks]([https://help.github.com/en/github/managing-files-in-a-repository/getting-permanent-links-to-files](https://help.github.com/en/github/managing-files-in-a-repository/getting-permanent-links-to-files))_
- [x] _Defined all the applicable weaknesses ([CWEs]([https://cwe.mitre.org/](https://cwe.mitre.org/)))_
- [x] _Proposed the CVSS vector items i.e. User Interaction, Attack Complexity_
- [x] _Checked that the vulnerability affects the latest version of the package released_
- [x] _Checked that a fix does not currently exist that remediates this vulnerability_
- [x] _Complied with all applicable laws_
