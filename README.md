# ansible-test
I needed a repository that I could build one time/one off playbooks in for ansible pull. This is prone to change and not for production.

ansible-pull -U https://github.com/zyzyx159/ansible-test.git -i "$(hostname --short),"