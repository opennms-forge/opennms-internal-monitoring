# Lab environment

Using AnyIP to make a large network avialable

```
ip r a local 10.0.0.0/12 dev lo
```

It gives you 1.048.576 addresses you can play with in your lab.
You can run the on a dedicated Linux box pretty easily and just set a network route to it from your OpenNMS Horizon box.

