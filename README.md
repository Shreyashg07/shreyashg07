class Identity:
    def __init__(self):
        self.name = "Shreyash"
        self.username = "@shreyashg07"
        self.alias = "CyberHive"  # Updated alias
        self.identity = [
            "Security Researcher",
            "Ethical Hacker",
            "VAPT Specialist",
            "Bug Bounty Hunter",
            "Digital Forensics Enthusiast"
        ]
        self.pronouns = "he/him"
        self.clearance = "Top Secret 🕵️‍♂️"
        self.threat_level = "Critical 🔥"
        self.arsenal = [
            "Penetration Testing",
            "Network Exploitation",
            "Digital Forensics",
            "Reverse Engineering"
        ]
        self.active_ops = [
            "Bug Bounty Recon",
            "CTF Challenges",
            "Malware Analysis"
        ]

    def whoami(self):
        profile = f"""
        ┌─[👨‍💻 {self.name}] - [{self.username}]
        ├─ Alias: {self.alias}
        ├─ Identity: {', '.join(self.identity)}
        ├─ Pronouns: {self.pronouns}
        ├─ Clearance: {self.clearance}
        ├─ Threat Level: {self.threat_level}
        ├─ Arsenal: {', '.join(self.arsenal)}
        ├─ Active Ops: {', '.join(self.active_ops)}
        └─ Status: 1337 (Elite)
        """
        return profile

if __name__ == "__main__":
    cyberhive = Identity()  # Changed variable name to CyberHive
    print(cyberhive.whoami())
