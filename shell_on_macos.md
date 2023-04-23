* Permitions enabler

 _Maybe:_ You will need to run this command with admin authority.

 ```shell
 xattr -r -d com.apple.quarantine ~/some/path/here
 ```

 We can use this command to provides permitions for all folder to run all commands into it. For example, when you install Java with JAVA_HOME definition. So you can just run:

 ```shell
 xattr -r -d com.apple.quarantine ${JAVA_HOME}
 ```
