# Bacula7-CentOS7-ansible
実行環境はCentOS7.2で確認済み<br>
<br>
鍵交換コマンド<br>
ssh-copy-id -i ~/.ssh/id_rsa.pub root@<サーバIPアドレス><br>
<br>
ansible実行コマンド<br>
ansible-playbook -i ansible_hosts bacula.yml<br>
<br>
以下のIPアドレスは環境に応じて変更してください。<br>
ansible_hosts<br>
roles/bacula/vars/main.yml
