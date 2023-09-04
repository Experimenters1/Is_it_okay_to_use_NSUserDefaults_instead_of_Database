# Is_it_okay_to_use_NSUserDefaults_instead_of_Database ?
## Is_it_okay_to_use_NSUserDefaults_instead_of_Database ?
#

[Is it okay to use NSUserDefaults instead of Database?](https://stackoverflow.com/questions/31870059/is-it-okay-to-use-nsuserdefaults-instead-of-database) <br><br>

[How to Store a Custom Object in User Defaults in Swift](https://cocoacasts.com/ud-5-how-to-store-a-custom-object-in-user-defaults-in-swift) <br><br>

#
### When I store data:<br>

1.User preference data: Settings,Accounts... - **NSUserDefaults** <br>
2.Security data：passwords - KeyChain
3.Small amount of data that do not need complex query - **Plist,Archiver** <br>
4.Big amount of data which need Structured Query － **Coredata/SQLite(FMDB)**. <br>


