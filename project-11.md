**ANSIBLE CONFIGURATION MANAGEMENT – AUTOMATE PROJECT 7 TO 10**

**Check your Ansible version by running ansible --version**

**![Ansible](./images/ansibleversion.PNG)**

**Configure Webhook in GitHub and set webhook to trigger ansible build**

**![webhookupdate](./images/webhookupdate.PNG)**

**ssh into your Jenkins-Ansible server using ssh-agent**

**using the code ssh -A ubuntu@public-ip**

**![connected](./images/connected.PNG)**

**using git commands  to add, commit and push your branch to GitHub**

**![gitcommand](./images/pushedtogit.PNG)**

**Once your code changes appear in master branch – Jenkins will do its job and save all the files (build artifacts) to /var/lib/jenkins/jobs/ansible/builds/<build_number>/archive/ directory on Jenkins-Ansible server.**

**![jenkinsupdate1](./images/jenkinsupdate1.PNG)**

**![jenkinsupdate2](./images/jenkinsupdate2.PNG)**

**checking the status of my wireshark with the code wireshark --version**

**![wireshark](./images/wireshackversion.PNG)**





