

```
make run
```

will build and run the jenkins instance.

you will then need to create a user for leeroy to use, and get that user's API Token.

Then update the jenkins cfg in `leeroy/config.json` and `make leeroy` to start leeroy.

set up the webhooks in the repos as per https://gist.github.com/jfrazelle/953b2664a484f1162722
