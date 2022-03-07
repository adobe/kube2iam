# About

We maintain a set of patches on top of upstream kube2iam. They need to be
semantically versioned as well so we understand, for example, that we're
upgrading a fix version of kube2iam vs a fix version of our patches.

The scheme followed has the upstream version then followed by our version:

```
K stands for upstream kube2iam version
A stands for Adobe's changes

{K major}.{K minor}.{K fix}-{A major}.{A minor}.{A fix}-adobe
```

# Changelog

## Mar 7, 2022 - 0.10.11-1.0.0-adobe

- add flag to optionally block ec2 metadata proxy ([#4](https://github.com/adobe/kube2iam/pull/4))
- Include the externalID in the cache key ([#5](https://github.com/adobe/kube2iam/pull/5))
