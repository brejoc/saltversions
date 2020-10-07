# saltversions

With saltversions you can see which version of Salt is in the 'interesting' Salt repositories in [OBS](build.opensuse.org/):

```
systemsmanagement:saltstack:products
systemsmanagement:saltstack:products:testing
systemsmanagement:saltstack:products:next
systemsmanagement:saltstack:products:next:testing
systemsmanagement:saltstack
systemsmanagement:saltstack:testing
openSUSE:Factory
```

# Usage

In order to use saltversions, you need to have an account at OBS and your credentials need to be available via environment variables: `OSCUSER` and `OSCPASS`. You can then just run the script and it will show you something like this:

```
systemsmanagement:saltstack:products
3000

systemsmanagement:saltstack:products:testing
3000

systemsmanagement:saltstack:products:next
3000.3

systemsmanagement:saltstack:products:next:testing
3000.3

systemsmanagement:saltstack
3000.3

systemsmanagement:saltstack:testing
3000.3

openSUSE:Factory
3000.3
```
