# Discourse NGI Emoticons

Auto installer for NGI emoji pack for Discourse

To install, edit the `containers/app.yaml` and add this repo in the plugins:

```
## Plugins go here
## see https://meta.discourse.org/t/19157 for details
hooks:
  after_code:
    - exec:
        cd: $home/plugins
        cmd:
          - git clone https://github.com/theCrius/discourse-ngi-emojis.git
```

It would be appreciated to know if you are using this pack somewhere :)
