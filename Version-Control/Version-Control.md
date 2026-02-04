<!-- ```text -->
<pre style="
  background:#0f172a;
  color:#e5e7eb;
  padding:20px;
  border-radius:12px;
  font-family: 'Fira Code', monospace;
  line-height:1.6;
  overflow-x:auto;
  white-space:pre-wrap;
">
VERSION CONTROL SYSTEMS (VCS) — SUMMARY NOTES

────────────────────────────────────────
WHAT IS A VERSION CONTROL SYSTEM?
────────────────────────────────────────
A Version Control System (VCS) is a tool that helps developers:
• Track changes in source code
• Collaborate without overwriting work
• Restore previous versions if needed
• Maintain project history

────────────────────────────────────────
CORE COMPONENTS OF VCS
────────────────────────────────────────
• Repository : Stores project files and full history
• Revision   : A saved version of the project
• Branch     : Separate line of development
• Commit     : Snapshot of changes at a time
• Merge      : Combine changes from branches

────────────────────────────────────────
TYPES OF VERSION CONTROL SYSTEMS
────────────────────────────────────────

1. LOCAL VERSION CONTROL SYSTEM
• Works only on one computer
• No collaboration
• No server or internet needed
• Suitable for personal projects

────────────────────────────────────────
2. CENTRALIZED VERSION CONTROL SYSTEM (CVCS)
────────────────────────────────────────
• Single central server stores code
• Developers checkout, modify, and commit
• Examples: SVN, CVS

ADVANTAGES:
• Easy to manage
• Centralized control
• Good for small teams

DISADVANTAGES:
• Single point of failure
• Server downtime stops work

────────────────────────────────────────
3. DISTRIBUTED VERSION CONTROL SYSTEM (DVCS)
────────────────────────────────────────
• Every developer has full copy
• Work can be done offline
• Two-step sharing process

WORKFLOW:
• Commit → Save locally
• Push   → Share with central repo
• Pull   → Get others’ changes

ADVANTAGES:
• No single point of failure
• Fast branching & merging
• Ideal for large & open-source projects

────────────────────────────────────────
POPULAR VERSION CONTROL SYSTEMS
────────────────────────────────────────

1. Git (DVCS)
• Most popular VCS
• Fast, flexible, decentralized
• Used with GitHub, GitLab, Bitbucket

2. Subversion (SVN) – CVCS
• Centralized repository
• Simple and controlled
• Used in enterprises

3. Mercurial (DVCS)
• Simple alternative to Git
• Fast and scalable

4. CVS (CVCS)
• One of the oldest VCS tools
• Limited features
• Mostly outdated today

5. Bazaar (DVCS)
• Supports centralized + distributed
• Beginner-friendly
• No longer actively developed

────────────────────────────────────────
FINAL CONCLUSION
────────────────────────────────────────
Version Control Systems are essential for modern software development.
Among all types, Distributed VCS (especially Git) is the most popular
due to flexibility, speed, and collaboration support.
```
