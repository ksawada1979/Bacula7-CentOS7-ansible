# Bacula-ansible-playbook
実行環境はCentOS6.6で確認済み<br>
<br>
Vagrant実行コマンド<br>
vagrant up bacula<br>
<br>
鍵交換コマンド<br>
ssh-copy-id -i ~/.ssh/id_rsa.pub vagrant@<サーバIPアドレス><br>
<br>
ansible実行コマンド<br>
ansible-playbook -i ansible_hosts bacula.yml<br>
<br>
以下のIPアドレスは環境に応じて変更してください。<br>
ansible_hosts<br>
Vagrantfile<br>
roles→bacula→vars<br>
