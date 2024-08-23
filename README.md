# iOS Compliance Policy
Instructions to create a basic iOS Compliance Policy
1)	Open the Microsoft Intune admin center
2)	Endpoint Security
3)	Compliance Policies
4)	Create a Policy
5)	Platform -> iOS/iPadOS -> Create
6)	Create a name, such as iOS Compliance Policy – test
7)	Enter Description with summary points of the policy -> Next
8)	Device Health -> block Jailbroken Devices
9)	System Security -> Require password to unlock mobile devices
10)	System Security -> Block simple passwords
11)	System Security -> Minimum password length (your choosing)
12)	System Security -> Required password type (alphanumeric) -> Next
13)	Mark Device as Non-Compliant -> Send email to user
14)	Schedule Days after non-compliance: leave at 0 because there is no consequences
15)	Message Template -> Device Non-Compliant (Sends a generic message listed in the details) - Next
16)	Add groups or users -> I chose group because I want the compliance policy to administer any iOS device under my Security Baseline group -> Next
17)	Review your policy and create
