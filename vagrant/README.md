`vagrant up` to get a box, then `vagrant ssh` to get in, then:

- Install maven:

```
curl -s "https://get.sdkman.io" | bash
source "$HOME/.sdkman/bin/sdkman-init.sh"
sdk install maven
```

Now, go to the shared folder and try stuff:

```
cd /vagrant_data
mvn clean test
```
