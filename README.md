# ansible
```bash
sudo apt update && sudo apt install curl && curl "https://raw.githubusercontent.com/mikeelindsay/.ansible-workstation/master/install?$(date +%s)" | bash && ansible-pull -U https://github.com/mikeelindsay/.ansible-workstation.git -t "NORUN" && clear && ansible-playbook ~/.ansible/pull/*/local.yml --ask-become-pass
```

```bash
ansible-pull -U https://github.com/mikeelindsay/.ansible-workstation.git -t "NORUN" && clear && ansible-playbook ~/.ansible/pull/*/local.yml --ask-become-pass
```

# adjust i3 dpi
```bash
echo "Xft.dpi: 172" > .Xresources && xrdb -merge ~/.Xresources && exec i3
```
