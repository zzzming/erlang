# Kerl
Like rvm for Ruby, nvm for Node.js, and virtualenv for Python we have now kerl for Erlang/OTP. [Kerl](https://github.com/kerl/kerl) allows to install and manage multiple OTP versions. kerl is written as a shell script and does not depend on Erlang.
But annoynce is JDK is required.
Here is another example of [Kerl steps](https://devminz.github.io/posts/devops/kerl-tool-for-erlangotp-version-management/)

The default build output file is at `~/.kerl/builds/<version>/

I created installation folder for Kerl build Erlang/OTP as supposed to Brewed that always installed under /usr/local/Cellar/erlang

`sudo kerl install 21.3 /Users/ming/kerl_otp/21.3
Installing Erlang/OTP 21.3 (21.3) in /Users/ming/kerl_otp/21.3...
You can activate this installation running the following command:
. /Users/ming/kerl_otp/21.3/activate
Later on, you can leave the installation typing:
kerl_deactivate`

