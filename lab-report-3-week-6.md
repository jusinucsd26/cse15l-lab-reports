# _Lab 2 Week 4_

---

# Streamlining ssh Configuration

> ## Part 1

![touchConfig](Screenshots/touchConfig.png)

- Open a new terminal

- Create a `config` file in the `.ssh` directory using the `touch` command

---

> ## Part 2

![vimConfig](Screenshots/vimConfig.png)

- Use the command `vim config` to modify the config text file

- Press `I` on keyboard to insert `Host ieng6 HostName ieng6.ucsd.edu User cs15lwi22zzz`

- Press `escape` key then `:wq` to exit out of vim

- Alternatively, you can do `open config` in the terminal and type the text

---

> ## Part 3

![sshIeng6](Screenshots/sshIeng6.png)

- Type ssh ieng6 on the terminal and you should be able to login to the UCSD computer

---

> ## Part 4

![scpIeng6](Screenshots/scpIeng6.png)

- Go into a directory with some file and secure copy the file to ieng6 with the command:

```
scp index.md ieng6:~/
```

<br>

[Return to Home Page](https://jusinucsd26.github.io/cse15l-lab-reports/)
