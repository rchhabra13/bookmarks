# CKA

General Kubernetes links live in [kubernetes.md](kubernetes.md).

## How people passed

- [How to ace the CKA exam in 7 days](https://medium.com/@writetomiglani/how-to-ace-the-certified-kubernetes-administrator-exam-in-7-days-e4603ac40746) (recommended)
- [How to pass the CKA exam](https://medium.com/bb-tutorials-and-thoughts/how-to-pass-the-certified-kubernetes-administrator-cka-exam-9e01f1aa93b8)
- [How I passed the CKA exam](https://medium.com/@krystiannowaczyk/how-i-passed-the-cka-certified-kubernetes-administrator-exam-f94b11566528)
- [My CKA experience](https://www.phillipsj.net/posts/my-cka-experience/)
- [CKA exam tips](https://myedes.io/cka-exam-tips/)
- [CKA exam de-stress guide](https://dev.to/t04glovern/certified-kubernetes-administrator-cka-exam-de-stress-guide-277k)
- [Tips and tricks for the CKA exam](https://sajidmoinuddin.com/2019/02/02/tips-tricks-for-certified-kubernetes-administrator-cka-exam/)
- [Learning materials and 8 tips to pass the CKAD exam](https://web.archive.org/web/20221127131026/https://wely-lau.net/2020/03/23/learning-materials-and-8-tips-to-pass-ckad-certified-kubernetes-application-developer-exam/) (archived copy)
- [Preparation and resources for the CKA exam](https://medium.com/faun/preparation-and-resources-for-cka-exam-ca868fc678c9)
  - [Useful exam bookmarks (gist)](https://gist.github.com/Piotr1215/016ba7218a1a949574786fb9b92382c1)
- [Preparing and passing the CKA exam](https://medium.com/@sovmirich/preparing-and-passing-the-certified-kubernetes-administrator-cka-exam-4a76fa4b1c4)

  > 8. The exam will be a question related to DNS and remember the following: in DNS Pod name is not the Hostname, but the IP address separated by hyphens. For example, 10-1-1-1.default.pod.cluster.local. This question is dealt with in Mumshad in lectures 147, 148, 149.
  > 9. Carefully study the topic of Static Pods, this will help you very well when troubleshooting the non-working Kubernetes components.
  > 10. TLS Bootstrapping. From my point of view the most voluminous question on the exam. It seemed to me more difficult than Mumshad described in his course and in the practical tests.

- [Tips and tricks to pass the CKA and CKAD exam (KodeKloud)](https://dev.to/kodekloud/tips-and-tricks-to-pass-the-cka-and-ckad-exam-c76)
  - Read these:
    - [Debug services](https://kubernetes.io/docs/tasks/debug/debug-application/debug-service/)
    - [Debug running pods](https://kubernetes.io/docs/tasks/debug/debug-application/debug-running-pod/)
    - [Determine the reason for pod failure](https://kubernetes.io/docs/tasks/debug/debug-application/determine-reason-pod-failure/)
- [Awesome CKA](https://github.com/krzko/awesome-cka)

## Concepts

- [Kubernetes concepts with pictures](https://github.com/Bes0n/CKA/blob/master/README.md) (recommended)
- [Kubernetes concepts docs](https://kubernetes.io/docs/concepts/)
- [Stupid Simple Kubernetes: Persistent Volumes explained by examples](https://medium.com/swlh/stupid-simple-kubernetes-persistent-volumes-explained-by-examples-29f8fec08c4)

## Exam environment setup

- [Vim shortcuts (gist)](https://gist.github.com/awidegreen/3854277)
- [Essential Vim for the CKAD or CKA exam](https://blog.codonomics.com/2019/09/essential-vim-for-ckad-or-cka-exam.html)

  ```vim
  " ~/.vimrc
  set number
  syntax on
  set syntax=yaml
  set et
  set sw=2 ts=2 sts=2
  ```

- Bash settings (`~/.bashrc`):

  ```bash
  source <(kubectl completion bash)
  source <(kubeadm completion bash)
  alias k=kubectl
  complete -F __start_kubectl k
  export do="--dry-run=client -oyaml"
  ```

- tmux
  - [Getting started with tmux](https://linuxize.com/post/getting-started-with-tmux/)
  - [Essential tmux for the CKAD or CKA exam](https://blog.codonomics.com/2019/09/essential-tmux-for-ckad-or-cka-exam.html)

    | Keys       | Action                                   |
    | ---------- | ---------------------------------------- |
    | `Ctrl+b c` | Create a new window (with shell)         |
    | `Ctrl+b w` | Choose window from a list                |
    | `Ctrl+b 0` | Switch to window 0 (by number)           |
    | `Ctrl+b ,` | Rename the current window                |
    | `Ctrl+b %` | Split current pane horizontally into two |
    | `Ctrl+b "` | Split current pane vertically into two   |
    | `Ctrl+b o` | Go to the next pane                      |
    | `Ctrl+b ;` | Toggle between current and previous pane |
    | `Ctrl+b x` | Close the current pane                   |

## Practice

- [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way)
- [Game of Pods (KodeKloud)](https://kodekloud.com/p/game-of-pods-game)
- [RX-M CKA online training](https://rx-m.com/cka-online-training/)
- [CKA practice environment](https://github.com/arush-sal/cka-practice-environment)
- [CKA lab practice](https://github.com/stretchcloud/cka-lab-practice)
- [CKA practice exercises](https://github.com/alijahnas/CKA-practice-exercises)
- [Kubernetes Certified Administrator curriculum notes](https://github.com/walidshaari/Kubernetes-Certified-Administrator)
- [CKAD exercises](https://github.com/dgkanatsios/CKAD-exercises)
- [CKAD practice questions](https://github.com/bbachi/CKAD-Practice-Questions)
- [Practice enough with these questions for the CKAD exam](https://medium.com/bb-tutorials-and-thoughts/practice-enough-with-these-questions-for-the-ckad-exam-2f42d1228552)
- [Practice examples and tips for CKA and CKAD](https://medium.com/@sensri108/practice-examples-dumps-tips-for-cka-ckad-certified-kubernetes-administrator-exam-by-cncf-4826233ccc27)
- [Practice questions (Google Doc)](https://docs.google.com/document/d/1o4qE9x4oXcqFgquUE1yYGJKhNmZnaeMR5SyxwjGGl1w/edit)
