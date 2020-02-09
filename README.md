Training Project to prepare for CKAD Exam
===================================================================

## Snippets


```
alias kc=kubectl 
alias kn='kubectl config set-context --current --namespace '
kc create deployment q1 --image=nginx --dry-run -o yaml >q1-tmpl.yaml
```

## Vim

```
$ cat <<EOF >>~/.vimrc
set tabstop=2
set expandtab
EOF
```
* Mark lines: Esc+V (then arrow keys)
* Copy marked lines: y
* Cut marked lines: d
* Past lines: p or P


## CKAD Resources

* [Practice Exam for Certified Kubernetes Application Developer (CKAD) Certification](https://matthewpalmer.net/kubernetes-app-developer/articles/ckad-practice-exam.html)
* [ckad-prep-notes](https://github.com/twajr/ckad-prep-notes)
* [ckad-tips](https://pnguyen.io/posts/ckad-tips/)
* [CKAD Exercises](https://github.com/dgkanatsios/CKAD-exercises)
* [The CKAD browser terminal](https://codeburst.io/the-ckad-browser-terminal-10fab2e8122e) and [simulator](https://killer.sh/)
* [Candidate Handbook (official)](https://training.linuxfoundation.org/wp-content/uploads/2019/04/CKA-CKAD-Candidate-Handbook-v1.18-March-2019.pdf)
* [Important tips (official)](https://training.linuxfoundation.org/wp-content/uploads/2019/05/Important-Tips-CKA-CKAD-4.30.19.pdf)
