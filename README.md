# In the Ubuntu terminal, install the Modular CLI:
curl https://get.modular.com | \
  MODULAR_AUTH=mut_a9e17400c8584fd695debb0f8bd4c40c \
  sh -

Before you start:

You must set the MODULAR_HOME and PATH environment variables, as described in the output when you ran modular install mojo. For example, if you’re using bash, you can set them as follows:
```bash
echo 'export MODULAR_HOME="$HOME/.modular"' >> ~/.bashrc
echo 'export PATH="$MODULAR_HOME/pkg/packages.modular.com_mojo/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```
If you have other issues during install, check our known issues.