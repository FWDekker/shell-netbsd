# shell-netbsd
Get a free shell for netbsd

If you need a netbsd VM shell, you can use this repo.


1. First fork this repo
2. Click the "Actions' menu on your Repo, and then enable github actions on your fork.
3. Then Select "All workflows" -> "shell" on the left.
4. Then click the "Run workflow" dropdown menu on the right side.
5. Then click the "Run workflow" button.


Wait a few seconds, the github action will run in your repo.

Click "Shell" -> "Start a netbsd shell",  to open the log window, you will see a netbsd vm is booting there.

Wait about 5-8 minutes, the netbsd vm will be ready.

And you will see the ssh address like below:

```
Setting up tmate...

Running tmate...

________________________________________________________________________________


To connect to this session copy-n-paste the following into a terminal:

ssh 3R7dS7j45xk4CGzkz52psXpqr@nyc1.tmate.io

After connecting you can run touch /tmp/keepalive to disable the 15m timeout
```

Good.  Use the address to connect:


```
ssh 3R7dS7j45xk4CGzkz52psXpqr@nyc1.tmate.io
```


You will get a shell like:


```
Mac-1606142911434:shell-netbsd runner$
```

Then you can ssh to the netbsd VM:

```
Mac-1606142911434:shell-netbsd runner$  ssh netbsd

```


# Under the hood

Uses: https://github.com/vmactions/netbsd-vm


